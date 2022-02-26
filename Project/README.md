# Digital Clock 
# Aim of project
* Designing a 7-digit digital clock using 7-sevensegment display, Atmega338 AVR microcontrollerand programming.
# Introduction-
A digital clock is a type of clock that displaysthe time numerically (i.e. in numerals), where as ananalog clock, displays the time by the positions of rotating hands.To represent the time, most digital clocks use aseven-segment LED or LCD for each of desireddigits. They also used other elements to indicatewhether the time is AM or PM, or simply use 12or 24 hour format. Some of the digital clock hasalarm function also. Now a days, they also includedate and day display.A digital clock is a type of clock that displays the time digitally, i.e. in numerals orother symbols, as opposed to an analog clock, where the time is indicated by the
positions of rotating hands.
#   Working  
The counting direction is always up (incrementing), and no counter clear isperformed. The counter simply overruns when it passes its maximum 8-bit value
(MAX = 0xFF) and then restarts from the bottom (0x00). In normal operation theTimer/Counter Overflow Flag (TOV0) will be set in the same timer clock cycle as the
TCNT0 becomes zero. The TOV0 Flag in this case behaves like a ninth bit, except that it is only set, not cleared. However, combined with the timer overflow interrupt that automatically clears the TOV0 Flag, the timer resolution can be increased by software. A new counter value can be written anytime. 


# Components
* 7 Segment display
   * The 7-segment display consists of seven LEDs arranged in a particular fashion in order to exhibit Decimal integers (0 – 9) & Hexadecimal characters (0 – F). Each of the seven LEDs is called a segment because when illuminated the segment forms part of a numerical digit.
* lcd display
      * LCD (Liquid Crystal Display) is a type of flat panel display which uses liquid crystals in its primary form of operation.It helps to monitor time and set alarm .
* atmega128
       * ATmega328P is a low-power CMOS 8-bit microcontroller based on the AVR enhanced RISC architecture. The ATmega328P achieves throughputs approaching 1MIPS per MHz By executing powerful instructions in a single clock cycle. This allows system designers to optimize power consumption versus processing speed very easily. ATMega328p is one of the famous MCUs of Atmel because of its use in the Arduino UNO board. ATmega328P is designed with low current consumption features. The chip contains 32 kilobytes of internal flash memory, 1KB of EEPROM, and 2KB of SRAM.
* aurdino uno 
     * Arduino UNO is a low-cost, flexible, and easy-to-use programmable open-source microcontroller board.It provides interface with lcd display.

## HIGH LEVEL REQUIREMENT
|Test ID  |    Description  |  
-------------|-----------------------------------
|HL01     |    helps to set alarm | 
|HL02     |    continous monitoring         |
|HL03     |    Higher response time  |
|HL04     |    Easy accessing time  |
|HL05     |    The projector must be able to store information or data |
## Low Level Requirement
|Test ID   |  Description | 
------------------|-------------------
|LL01     | The projector should have low power consumption |
|LL02   | The projector must not get overheated |
## SWOT Analysis
* Strengths
    * continous monitor of time 
    
* Weakness
    * Sensitive materials need to update more for high level puposes.
* Opportunity 
   * To sophiticated people and common people to perform daily routine.
   * for scientists can set alarm for performing projects.
   
* Threats
   * Due to sensitivity there may be a threat.
## 4 W's and 1 H
 # Who
  * to all people: common people, scientists.
  # What
     * Monitors time continously.
     * useful to set alarm.
  # When
  * daily routine purposes, experimental purposes. 
  # Where
      * Useful to everyone and everywhere.
  # How 
     * Implementation of clock and setting alarm for specific time.
   ## Mode of operation
   * Digital clock operation using ATmega328, an AVR Processor based microcontroller unit

*   You can use a digital clock, stopwatch, alarm, down count timer, and calculator

• Designed the Atmega128 Board and wrote the software programs in C language

• The Board had Atmega128 Micro Controller, 7-Segment, SN74LS47, Resistor, Diode, 7805 Regulator, Capacitor, LED, Button, and Buzzer

• Mode 0 (Digital Clock): The most basic purpose is a digital clock using a timer. 7-segment is 10min, min, 10s, 1s, 10ms. It is arranged in order of 1ms, and the time is counted

• Mode1 (StopWatch): This function records the time and includes the Lap_time. The stopwatch function turns on the LED and counts from 1s. Use switch2 and 3 to count the numbers

• Mode2 (Alarm): Sets the alarm of the digital clock. After setting the time using switch2 and 3 as the alarm function, the buzzer sounds when the timer reaches mode 0

• Mode3 (Down Count Timer): Timer to count down from the set time to 0. If you set the time using switch2 and 3 as the DownCounter, the buzzer will sound when the count goes down to 00

• Mode4 (Calculator): A calculator performs arithmetic operations. Enter two digits using switch2 and 3 to achieve the desired arithmetic operation with switch6
  
  


# Applications 
*  cars
*  radios
*  televisions,
*  microwave ovens
*   standard ovens
*   computers 
*  cell phones.  
