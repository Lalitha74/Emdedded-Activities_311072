## Emdedded-Activities_311072
## SeatHeatingApplication
## Activity_1
## If the person sit in the car seat then the ButtonSensor activate and if the person turns ON the heater then LED Glows
|ON|OFF|
|:--:|:--:|
|![ON](https://user-images.githubusercontent.com/62166597/115904289-3d88a080-a482-11eb-8dac-4baad5d98b64.PNG)|![OFF](https://user-images.githubusercontent.com/62166597/115904238-2e095780-a482-11eb-99fa-67ae25f4005d.PNG)|
## Activity_2
## If both the above conditions are true, then input analog temperature readings are converted into digital values.
![ADC](https://user-images.githubusercontent.com/85540441/127325146-e45f0d5b-9173-4669-bcef-7cc735d272af.png)
## Activity_3
## Using PWM the digital values are shown in Oscilloscope
|PWM_20%|PWM_40%|
|:--:|:--:|
|![PWM_20%](https://user-images.githubusercontent.com/85540441/127325740-902f3538-a1d0-46e7-8c9b-b015f2565e37.png)|![PWM_40%](https://user-images.githubusercontent.com/85540441/127325787-d806d9f6-56aa-4d48-bb18-0d1d36f77b60.png)
|PWM_70%|PWM_95%|
|   |   |
![PWM_70%](https://user-images.githubusercontent.com/85540441/127325848-6445b58f-727f-4bf3-88a4-a5b7eee9aa98.png)|![PWM_95%](https://user-images.githubusercontent.com/85540441/127325926-b8e7bfc2-e619-4f55-933b-cb56376f3e2f.png)
## Activity_4
## The digital temperature values can be visualized in serial monitor using USART protocol
![serial communication](https://user-images.githubusercontent.com/85540441/127324544-94917683-705e-4df5-8333-6ec753d91eb4.png)
## Functioning of Application
![function Application](https://user-images.githubusercontent.com/85540441/127324870-8ef9ecd0-55a7-4353-9411-d1b2f312ac81.gif)
## CI and Code Quality
|Build|Cppcheck|Codacy|Code Inspector|Code Grade|
|:--:|:--:|:--:|:--|:---|
[![Compile-Linux](https://github.com/Lalitha74/Emdedded-Activities_311072/actions/workflows/compile.yml/badge.svg)](https://github.com/Lalitha74/Emdedded-Activities_311072/actions/workflows/compile.yml)|[![Cppcheck](https://github.com/Lalitha74/Emdedded-Activities_311072/actions/workflows/CodeQuality.yml/badge.svg)](https://github.com/Lalitha74/Emdedded-Activities_311072/actions/workflows/CodeQuality.yml)|[![Codacy Badge](https://app.codacy.com/project/badge/Grade/8ef572e5cf5d404d9f2e908e0efc071b)](https://www.codacy.com/gh/Lalitha74/Emdedded-Activities_311072/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Lalitha74/Emdedded-Activities_311072&amp;utm_campaign=Badge_Grade)|![image](https://user-images.githubusercontent.com/86546222/127517697-43514b08-b769-4323-9bf0-0d3e30d48645.png)|![image](https://user-images.githubusercontent.com/86546222/127517749-2b1f3516-42fe-4b73-a0dd-9f6d4a3443b2.png)





