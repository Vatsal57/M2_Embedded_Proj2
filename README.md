# M2_Embedded_Tempsensor
[![cppcheck-action-test](https://github.com/Vatsal57/M2_Embedded_Tempsensor/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/Vatsal57/M2_Embedded_Tempsensor/actions/workflows/cppcheck.yml)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/3e0c7edc64e140a59ece97b7f14bfa63)](https://www.codacy.com/gh/Vatsal57/M2_Embedded_Tempsensor/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Vatsal57/M2_Embedded_Tempsensor&amp;utm_campaign=Badge_Grade)


The operation of the heat control system is coded in embedded c and the working is demonstrated using a simuation software called **SimulIDE**.

This system is usually done in 3 steps or in 3 activities

*   When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
*   Then the analog input from the temperature sensor is received and digitized using ADC.
*   The digitized temperature input is visualized using Pulse Width Modulation.
 
