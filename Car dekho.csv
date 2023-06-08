use cars;

-- 1.read data --

select * from car_dekho;

-- 2.Total Cars: to get a count of total records --

select count(*) from car_dekho;

-- 3.The manager asked the employee how many cars will be available in 2023? --

select count(*) from car_dekho where year = 2023;

-- 4.The manager asked the employee how many cars will be available in 2020,2021 and 2022 --

select count(*) from car_dekho where year in (2020,2021,2022) group by year;

-- 5.Client asked me to print the total of all cars by year--

select year,count(*) from car_dekho group by year;

-- 6.Client asked to car dealer agent,how many diesel cars will be in 2020?--

select count(*) from car_dekho where year = 2020 and fuel = "diesel";

-- 7.client asked to car dealer agent,how many petrol cars will be in 2021,2022 and 2023? --

select year, count(*) from car_dekho where year in (2021,2022,2023) and fuel = "petrol" group by year;

-- 8.The manager asked the employee to print all the fuel cars(petrol,diesel and electric) by all year --

-- PETROL --

select year, count(*) from car_dekho where fuel = "petrol" group by year;

-- DIESEL --

select year, count(*) from car_dekho where fuel = "diesel" group by year;

-- ELECTRIC --

select year, count(*) from car_dekho where fuel = "electric" group by year;

-- 9.Manager said there were more than 250 cars in a year, which year was it? --

select year, count(*) from car_dekho group by year having count(*) > 250;

-- 10.Manager said there were less than 100 cars in a year, which year was it? --

select year, count(*) from car_dekho group by year having count(*) < 100;

-- 11.The manager said to the employee all car count details from 2015 to 2023, we need a complete list --

select count(*) from car_dekho where year between 2015 and 2023;

-- 12.The manager said the employee all car details from 2010 to 2023 --

select * from car_dekho where year between 2010 and 2023;





