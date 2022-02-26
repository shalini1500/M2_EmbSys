# Digital Clock 
# Aim of project
* Designing a 7-digit digital clock using 7-sevensegment display, Atmega328P AVR microcontrollerand programming.
# Introduction-
A digital clock is a type of clock that displaysthe time numerically (i.e. in numerals), where as ananalog clock, displays the time by the positions of rotating hands.To represent the time, most digital clocks use aseven-segment LED or LCD for each of desireddigits. They also used other elements to indicatewhether the time is AM or PM, or simply use 12or 24 hour format. Some of the digital clock hasalarm function also. Now a days, they also includedate and day display.A digital clock is a type of clock that displays the time digitally, i.e. in numerals orother symbols, as opposed to an analog clock, where the time is indicated by the
positions of rotating hands.
#   Working  
The counting direction is always up (incrementing), and no counter clear isperformed. The counter simply overruns when it passes its maximum 8-bit value
(MAX = 0xFF) and then restarts from the bottom (0x00). In normal operation theTimer/Counter Overflow Flag (TOV0) will be set in the same timer clock cycle as the
TCNT0 becomes zero. The TOV0 Flag in this case behaves like a ninth bit, except that it is only set, not cleared. However, combined with the timer overflow interrupt that automatically clears the TOV0 Flag, the timer resolution can be increased by software. A new counter value can be written anytime. 


# components
* 7 Segment display.
* lcd display
* atmega128
* aurdino uno
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
  
  


# Applications 
*  cars
*  radios
*  televisions,
*  microwave ovens
*   standard ovens
*   computers 
*  cell phones.  
