ITS
===

* Australia: http://livetraffic.rta.nsw.gov.au/desktop.html#textview
* Camera spec: http://en.wikipedia.org/wiki/Traffic_camera
* Central software:http://en.wikipedia.org/wiki/IRIS_(transportation_software)



Overview: http://www.youtube.com/watch?v=oQpU39CyLa0

Details here: http://en.wikipedia.org/wiki/Intelligent_transportation_system

# Key words: 

Urban traffic signal control (UTC), optimized traffic signal control, lane management, auto alarm, saturation, cycle time, green time,
merci extension of green

Traffic variables (such as headway, speed, density) 

Traffic light: set it and forget it

Fiber network, ITS express: http://www.itsexpress.com/

It may be appropriate to use different values for the same vehicle type according to circumstances. For example, in the UK in the 1960s and 1970s, bicycles were evaluated thus:

* on rural roads 0.5
* on urban roads 0.33
* on roundabouts 0.5
* at traffic lights 0.2

PTZ camera

# Modeling goals
* Simulation
* Optimisation
* Modeling levels
* Lane
* Road
* Intersection
* Network

* Turning behavior
* PCE: http://en.wikipedia.org/wiki/Passenger_car_equivalent
* PCU Passenger Car Unit

# Traffic pattern

Inputs: Volume, occupancy, speed, queue length, vehicle type, images

Outputs: charts

* Level: lane, intersection/ area/ region/city
* Aggregation: daytime
  * Time: 5 minute/hour/day/week/month
  * Type
  * Speed range

CCTV, Detection camera: height 8-10 m, 4 lane wide, 2 lane queue length, near stop line

Centrialized communication: ADSL, 256 Kbps, KPIs(volume,speed, queue length) time interval: 5 minutes, images interval: 1 minute

**Visualization**

Grid view:
Intersection name:
[Direction]   [Queue length]    [Avg.speed]   [Traffic volume]    [Queue max]   [Image sample]

Unit of measure:  
* Queue: m/5 minutes
* Volume: vehicles/ 5 minutes

Chart view:
* Queue length / time
* Speed distribution: volume of each type(car,bike) / speed range
* Classified traffic volume: volume / day time
* Traffic data: Volume(vehicle/5 minutes), Speed(km/h), Occupancy(%)
* Inbound/Outbound peak: given intersection: volume/time period
* Peak period: given map with hot spots: time period of peak
* Lane-by-lane: balanced or unbalanced lane?

Lane management
Estimated cycle length

Cycle time in bangkok(500s, 400s in peak periods), in Western 180-240s
Traffic pattern at each intersection is various
Queue length: network experiences whether oversaturation -> estimate cycle length -> optimal flow

**Occupancy calculation**

Having vehicle size = 4m, speed = 60Km/h, flow rate is 1200 vehicle/hour, what is relative occupancy?
* vehicle in space: flow rate/ speed = 1200/60 = 20 vehicles/km ~ 1 vehicle -> 50 m
* Real size / given space: 4/50 = 8%


# Picks

* Straddling BRT in China: http://www.youtube.com/watch?v=hShxp_apW24
* Phantom traffic jam: http://www.youtube.com/watch?v=goVjVVaLe10
* Congestion charge on traffic jam: http://www.youtube.com/watch?v=CX_Krxq5eUI
-- non linear pattern
-- Stockholm, 2006: 70% supporters, 20% changed route
-- `don't tell people to adapt, nudge them instead`

# Traffic signal control (TSC)

Wiki: http://en.wikipedia.org/wiki/Traffic_light_control_and_coordination

# Vietnam characteristics

* mixed lanes
* large portion of bikes
* behavorial culture/awareness
* as flexible as possible, no silver bullet, 1 fits all sizes


# Technologies

* Wireless communication: http://www.ivcco.com/products/specialized-industrial-certified-products/
* Computational: from PLC to industry PC/board
* Floating things(car/mobile) data
* Sensors based
* Video processing based

# Applications

* ETC: tolling collection
* Dynamic traffic light sequence
* Automatic road enforcement
* VSL: variable speed limit
* VDS: vehicle detection system
* Collision avoidance system
* Emergency notification system

# Basic flow
1. prototype
2. field test prototype
3. Demo
4. Pilot
5. Expansion
6. Advance
7. Optimized

# References
* http://www.oregon.gov/ODOT/HWY/TRAFFIC-ROADWAY/docs/pdf/guidelines_for_vms_on_state_highway.pdf
* http://global-sei.com/its/common/pdf/2012_ITSAP_1.pdf
* http://global-sei.com/tr/pdf/info/60-10.pdf
* http://www.easts.info/on-line/proceedings_05/1367.pdf
* Forth in Thailand: http://www.gets.co.th/en/pdf/ATC/ATC_en.pdf
* http://www.atransociety.com/2013/pdf/5thSymposiumDownloadable/FullPaper/2D/SCS12-010.pdf
* Traffic Signal Control System: http://ntl.bts.gov/lib/jpodocs/edldocs1/13480/ch3.pdf
* http://en.wikipedia.org/wiki/Traffic_light_control_and_coordination
* http://www.mech.kuleuven.be/cib/verkeer/dwn/H111part3.pdf
* http://www.mautc.psu.edu/docs/mautc-2008-02.pdf
