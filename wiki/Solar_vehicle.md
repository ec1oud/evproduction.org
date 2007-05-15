---
title: b'Solar vehicle'
permalink: b'wiki/Solar_vehicle/'
layout: wiki
tags:
 - Solar vehicles
---

A **solar car** is an [electric vehicle](electric_vehicle "wikilink")
powered by [solar energy](solar_power "wikilink") obtained from solar
panels on the surface of the car.
[Photovoltaic](/wiki/Photovoltaic "wikilink") (PV) cells convert the sun's
energy directly into [electrical energy](electrical_energy "wikilink").
Solar cars are not practical day-to-day transportation devices at
present, but are primarily demonstration vehicles and engineering
exercises. Solar cars compete in races (often called *rayces*) such as
the [World Solar Challenge](/wiki/World_solar_challenge "wikilink") and the
[American Solar Challenge](/wiki/American_Solar_Challenge "wikilink"). These
events are often sponsored by government agencies, such as the [United
States Department of
Energy](/wiki/United_States_Department_of_Energy "wikilink"), who are keen to
promote the development of alternative energy technology (such as [solar
cells](solar_cells "wikilink")). Such challenges are often entered by
universities to develop their students' engineering and technological
skills, but many professional teams have entered competitions as well,
including teams from [GM](/wiki/General_Motors_Corporation "wikilink") and
[Ford](/wiki/Ford_Motor_Company "wikilink").

### Design

Solar cars combine technology typically used in the
[aerospace](aerospace "wikilink"), [bicycle](bicycle "wikilink"),
[alternative energy](alternative_energy "wikilink") and
[automotive](automotive "wikilink") industries. Unlike typical race
cars, solar cars are designed with severe [energy](energy "wikilink")
constraints imposed by the race regulations. These rules limit the
energy to only that collected from [solar
radiation](solar_radiation "wikilink") and as a result optimizing the
design to account for aerodynamic drag, vehicle weight, rolling
resistance and electrical efficiency are paramount. Conventional
thinking has to be challenged, for example, rather than a conventional
automobile seat which would weigh tens of pounds, one [solar
car](1993_"Maize_&_Blue"_University_of_Michigan_Solar_Car "wikilink")
designed by Ford and General Motors for [University of
Michigan](/wiki/University_of_Michigan "wikilink") employed a
[nylon](nylon "wikilink") mesh seat combined with a five-point harness
that weighed less than 3 pounds.

The design of a solar car is governed by the power equation:

$$\\eta \\left\\{\\eta\_bE + \\frac{Px}{v}\\right\\} = \\left\\{W C\_{rr^1} + N C\_{rr^2} v + \\frac{1}{2}\\rho C\_d A v^2\\right\\}x +Wh + \\frac{N\_a W v^2}{2g}$$
[1]

Briefly, the left hand side represents the energy input into the car
(batteries and power from the sun) and the right hand side is the energy
needed to drive the car along the race route (overcoming rolling
resistance, aerodynamic drag, going uphill and accelerating). Everything
in this equation can be estimated except *v*. The parameters include:

*η*
= Motor, controller and drive train efficiency (decimal)  
*η*<sub>*b*</sub>
= Watt-hour battery efficiency (decimal)  
::E = Energy available in the batteries (joules)  
::P = Estimated average power from the array (watts)  
::x = Daily race route distance (meters)  
::W = Weight of the vehicle (newtons)  
*C*<sub>*r**r*<sup>1</sup></sub>
= First coefficient of rolling resistance (non-dimensional)  
*C*<sub>*r**r*<sup>2</sup></sub>
= Second coefficient of rolling resistance (newton-seconds per meter)  
::N = Number of wheels on the vehicle (integer)  
*ρ*
= Air density (kilograms per cubic meter)  
*C*<sub>*d*</sub>
= Coefficient of drag (non-dimensional)  
::A = Frontal area (meters squared)  
::h = Total height that the vehicle will climb (meters)  
*N*<sub>*a*</sub>
= Number of times the vehicle will accelerate in a race day (integer)  
::g = Gravity constant (meters per second squared)  
::v = Average velocity over the route (meters per second)  
Solving the equation for velocity results in a large equation
(approximately 100 terms). Using the power equation as the arbiter,
vehicle designers can compare various car designs and evaluate the
comparative performance over a given route. Combined with
[CAD](/wiki/CAD "wikilink") and systems modeling, the power equation is a
useful tool in solar car design.

### Driver's cockpit

The driver's cockpit usually only contains a single seat, although a few
cars do contain room for a second passenger. They contain some of the
features available to drivers of traditional vehicles such as
[brakes](brakes "wikilink"), accelerator, turn signals, rear view
mirrors (or camera), ventilation, and sometimes [cruise
control](cruise_control "wikilink"). A radio for communication with
their support crews is almost always included.

Solar cars are often fitted with gauges as seen in conventional cars.
Aside from keeping the car on the road, the driver's main priority is to
keep an eye on these gauges to spot possible problems. Cars without
gauges available for the driver will almost always feature wireless
telemetry. Wireless telemetry allows the driver's team to monitor the
car's energy consumption, solar energy capture and other parameters and
free the driver to concentrate on just driving. Drivers also have a
[safety harness](safety_harness "wikilink"), and optionally (depending
on the race) a helmet similar to racing car drivers. But they don't go
200 mph

cook pit

### Electrical system

The electrical system is the most important part of the car's systems as
it controls all of the power that comes into and leaves the system. The
[battery pack](battery_pack "wikilink") plays the same role in a solar
car that a petrol tank plays in a normal car in storing power for future
use. Solar cars use a range of batteries including [lead-acid
batteries](lead-acid_batteries "wikilink"), nickel-metal hydride
batteries ([NiMH](/wiki/NiMH "wikilink")), Nickel-Cadmium batteries
([NiCd](/wiki/NiCd "wikilink")), [Lithium ion
batteries](/wiki/Lithium_ion_battery "wikilink") and [Lithium polymer
batteries](/wiki/Lithium_polymer_batteries "wikilink"). Lead-acid batteries
are less expensive and easier to work with but have less power to weight
ratio. Typically, solar cars use voltages between 84 and 170 volts.

Power electronics
[monitor](http://www.raztec.co.nz/Solar%20Fern%20Project.aspx) and
regulate the car's electricity. Components of the power electronics
include the peak power trackers, the motor controller and the data
acquisition system.

The peak power trackers manage the power coming from the [solar
array](solar_array "wikilink") to maximize the power and deliver it to
be stored in the motor. They also protect the batteries from
overcharging. The motor controller manages the electricity flowing to
the motor according to signals flowing from the accelerator.

Many solar cars have complex data acquisition systems that monitor the
whole electrical system while even the most basic cars have systems that
provide information on battery voltage and current to the driver. One
such system utilizes [Controller Area
Network](/wiki/Controller_Area_Network "wikilink") (CAN).

### Drivetrain

The setup of the motor and
[transmission](/wiki/Transmission_(mechanics) "wikilink") is unique in solar
cars. The [electric motor](electric_motor "wikilink") normally drives
only one wheel (usually at the back of the car) due to the low amount of
power it generates. Solar car motors are normally rated at between 2 and
10 hp (1 and 7.5 kW); the most common type of motor is a dual-winding DC
brushless. The dual-winding motor is sometimes also used as a
transmission because multi-geared transmissions are rarely used.

There are three basic types of transmissions used in solar cars:

-   a single reduction direct drive
-   a variable ratio drive belt
-   a direct drive transmission (hub motor)

There are several varieties of each type. The most common is the direct
drive transmission.

### Mechanical systems

The mechanical systems are designed to keep friction and weight to a
minimum while maintaining strength. Designers normally use titanium and
composites to ensure a good strength-to-weight ratio.

Solar cars usually have three wheels, but some have four. Three wheelers
usually have two front wheels and one rear wheel: the front wheels steer
and the rear wheel follows. Four wheel vehicles are set up like normal
cars or similarly to three wheeled vehicles with the two rear wheels
close together.

Solar cars have a wide range of
[suspensions](suspension_(vehicle) "wikilink") because of varying bodies
and chassis. The most common front suspension is the double-A-arm
suspension found in traditional cars. The rear suspension is often a
trailer-arm suspension found in motor cycles.

Solar cars are required to meet rigorous standards for brakes. [Disc
brakes](/wiki/Disc_brakes "wikilink") are the most commonly used due to their
good braking ability and ability to adjust. Mechanical and hydraulic
brakes are both widely used with the brakes designed to move freely by
minimise brake drag.

Steering systems for solar cars also vary. The major design factors for
steering systems are efficiency, reliability and precision alignment to
minimise tire wear and power loss. The popularity of solar car racing
has led to some tire manufacturers designing tires for solar vehicles.
This has increased overall safety and performance.

### Solar array

The solar array consists of hundreds of photovoltaic [solar
cells](solar_cells "wikilink") converting sunlight into electricity.
Cars can use a variety of solar cell technologies; most often
polycrystalline silicon, monocrystalline silicon, or gallium arsenide.
The cells are wired together into strings while strings are often wired
together to form a panel. Panels normally have voltages close to the
nominal battery voltage. The main aim is to get as many cells in as
small a space as possible. Designers encapsulate the cells to protect
them from the weather and breakage.

Designing a solar array is more than just stringing bunch of cells
together. A solar array acts like a lot of very small batteries all
hooked together in series. The total voltage produced is the sum of all
cell voltages. The problem is that if a single cell is in shadow it acts
like a [diode](diode "wikilink"), blocking the flow of current for the
entire string of cells. To correct against this, array designers use
by-pass diodes in parallel with smaller segments of the string of cells,
allowing current to flow around the non-functioning cell(s). Another
consideration is that the battery itself can force current backwards
through the array unless there are blocking diodes put at the end of
each panel.

The power produced by the solar array depends on the weather conditions,
the position of the sun and the capacity of the array. At noon on a
bright day, a good array can produce over 2 kilowatts (2.6 hp).

Some cars have employed free standing or integrated
[sails](sails "wikilink") to harness wind energy[2], which is allowed by
the race regulation.

### Bodies and chassis

Solar cars have very distinctive shapes as there are no established
standards for design. Designers aim to minimize
[drag](drag_(physics) "wikilink"), maximize exposure to the sun,
minimize weight and make vehicles as safe as possible.

In [chassis](chassis "wikilink") design the aim is to maximize strength
and safety while keeping the weight as low as possible. There are three
main types of chassis:

-   [space frame](space_frame "wikilink")
-   semi-monocoque or carbon stream
-   [monocoque](monocoque "wikilink")

The space frame uses a welded tubed structure to support the body which
is a lightweight composite shell attached to the body. The
semi-monocoque bulkheads to support the weight and is integrated into
the belly with the top sections often being attached to the body. A
monocoque structure uses the body of the car as an integrated load
bearing structure.

[Composite materials](/wiki/Composite_material "wikilink") are widely used in
solar cars. [Carbon fiber](/wiki/Carbon_fiber "wikilink"),
[Kevlar](/wiki/Kevlar "wikilink") and [fiberglass](fiberglass "wikilink") are
common composite structural materials while foam and honeycomb are
commonly used filler materials. [Epoxy](/wiki/Epoxy "wikilink") resins are
used to bond these materials together. Carbon fiber and Kevlar
structures can be as strong as steel but with a much lighter weight.

Race strategy
-------------

Optimizing energy consumption is of prime importance in a solar car
race. Therefore it is very important to be able to closely monitor the
speed, energy consumption, energy intake from solar panel, among other
things in real time. Some teams employ sophisticated
[telemetry](telemetry "wikilink") that relays vehicle performance data
to a computer in a following support vehicle.

The strategy employed depends upon the race rules and conditions. Most
solar car races have set starting and stopping points where the
objective is to reach the final point in the least amount of total time.
Since aerodynamic [drag](drag "wikilink") rises exponentially with
speed, the energy the car consumes also rises exponentially. This simple
fact means that the optimum strategy is to travel at a single steady
speed during all phases of the race. Given the varied conditions in all
races and the limited (and continuously changing) supply of energy, most
teams have race speed optimization programs that continuously update the
team on how fast the vehicle should be traveling.

Solar car races
---------------

![[University of
Michigan](/wiki/University_of_Michigan_Solar_Car_Team "wikilink") and
[University of
Minnesota](/wiki/University_of_Minnesota_Solar_Vehicle_Project "wikilink")
heading west toward the finish line in the North American Solar
Challenge
2005](IMG_0095.jpg "fig:University of Michigan and University of Minnesota heading west toward the finish line in the North American Solar Challenge 2005")
The two most notable solar car races are the [World Solar
Challenge](/wiki/World_Solar_Challenge "wikilink") and the [North American
Solar Challenge](/wiki/American_Solar_Challenge "wikilink"). They are
contested by a variety of university and corporate teams. Corporate
teams contest the race to give its design teams experience in working
with both alternative energy sources and advanced materials (although
some may view their participation as mere
[PR](public_relations "wikilink") exercises). GM and Honda are among the
companies who have sponsored solar teams. University teams enter the
races because it gives their students experience in designing high
technology cars and working with environmental and advanced materials
technology. These races are often sponsored by agencies such as the US
Department of Energy keen to promote renewable energy sources.

The cars require intensive support teams similar in size to professional
motor racing teams. This is especially the case with the World Solar
Challenge where sections of the race run through very remote country.

There are other races, such as [Suzuka](/wiki/Suzuka_Circuit "wikilink"),
[Phaethon](/wiki/Phaethon "wikilink"), and the [World Solar
Rally](2006_World_Solar_Rally_in_Taiwan "wikilink"). Suzuka is a yearly
track race in [Japan](/wiki/Japan "wikilink") and Phaethon was part of the
Cultural Olympiad in [Greece](/wiki/Greece "wikilink") right before the [2004
Olympics](2004_Olympics "wikilink").

The 2005 North American Solar Challenge, which ran from Austin, Texas,
to Calgary, Canada, was the successor of the American Solar Challenge.
The ASC ran in 2001 and 2003 from Chicago, Illinois, to Claremont,
California along old Route 66. The ASC was in turn the successor to the
old GM Sunrayce, which was run across the country in 1990, 1993, and
then every two years through 1999.

The 2005 North American Solar Challenge had two classes:

-   Open: where teams are allowed to use space-grade solar cells - won
    by the [University of
    Michigan](/wiki/University_of_Michigan_Solar_Car_Team "wikilink").
-   Stock: limits the type of cells that can be used on solar arrays -
    won by [Stanford University](/wiki/Stanford_solar_car_project "wikilink").

The North American Solar Challenge was sponsored in part by the US
Department of Energy. However, funding was cut near the end of 2005, and
the 2007 NASC will not happen. Recently, however, prospects of a
NASC-like race in 2008 are looking up. 18 teams from around North
America attended a conference in Topeka, KS on October 20-21 to decide
upon rules for a 2008 race. Assuming that funding is found, this race is
fairly sure to occur.

The 20th Anniversary race of the World Solar Challenge will be run in
October of 2007, and is already shaping up to be a race to remember.
Major regulation changes were released in June 2006 for this race,
intended to slow down cars in the main event, which had been approaching
the speed limit in previous years.

Solar bicycles and motorcycles
------------------------------

The first solar "cars" were actually tricycles or quadricycles built
with bicycle technology. These were called solarmobiles at the first
solar race, the Tour de Sol in Switzerland in 1985 with about 60
participants, 30 using exclusively solar power and 30
solar-human-powered hybrids. A few true solar bicycles were built,
either with a large solar roof, a small rear panel, or a trailer with a
solar panel. Later more practical solar bicycles were built with
foldable panels to be set up only during parking. Even later the panels
were left at home, feeding into the electric mains, and the bicycles
charged from the mains. Today highly developed [electric
bicycles](motorized_bicycle "wikilink") are available and these use so
little power that it costs little to buy the equivalent amount of solar
electricity. The "solar" has evolved from from actual hardware to an
indirect accounting system. The same system also works for electric
motorcycles, which were also first developed for the Tour de Sol.

Practical applications
----------------------

Solar cars achieve their performance by extreme lightness of weight, and
very efficient aerodynamics that force compromises that would not be
acceptable in a day-to-day transportation device. Any vehicle built for
passenger comfort and meeting contemporary safety standards would be
much less aerodynamic and much heavier, thus requiring much more power
to achieve highway speeds. Therefore, with current and foreseeable
technologies it is unlikely a pure solar car will become commercially
available. However, solar cars are essentially electric cars with an
inbuilt recharging capability, so some of the engineering knowledge and
technology developed in competition solar cars may help the development
of [battery electric vehicles](battery_electric_vehicles "wikilink") and
even [hybrid vehicles](hybrid_vehicles "wikilink"). The Venturi AstroLab
in 2006 was hailed as the world's first commercial electro-solar hybrid
car due to be released in January 2008.[3]

The question arises as to whether, if [battery electric
vehicles](battery_electric_vehicles "wikilink") become popular, it will
be worthwhile fitting them with solar cells to extend their range and
allowing recharge while parked anywhere in the sun. However, with
present and near-term engineering considerations, it seems that the best
place for solar cells will generally be on the roofs of buildings, where
they are always exposed to the sky and weight is largely irrelevant,
rather than on vehicle roofs.

One practical application for solar powered vehicles is possibly golf
carts, some of which are used relatively little but spend most of their
time parked in the sun.

See also
--------

-   [List of solar car teams](/wiki/List_of_solar_car_teams "wikilink")
-   [Race the Sun](/wiki/Race_the_Sun "wikilink")
-   [Solar airplane](/wiki/Solar_airplane "wikilink")

Notes
-----

<references/>

External links
--------------

-   [Solar Car Wiki](http://scg.levels.unisa.edu.au/src) ([University of
    South Australia](/wiki/University_of_South_Australia "wikilink"))
-   [Howstuffworks.com : How solar cars
    work](http://videos.howstuffworks.com/2007-naias-solar-car-video.htm)
-   [Solar Decathlon Web
    site](http://www.eere.energy.gov/solar_decathlon/).
    -   [DOE announced that the third Solar Decathlon competition will
        be held from 2007-October 12th through the
        20th](http://www.energy.gov/news/5026.htm) in [Washington,
        D.C](/wiki/Washington,_D.C "wikilink").
-   [Solar cars in
    inventors.about.com](http://inventors.about.com/od/sstartinventions/a/Solar_Cars.htm)
-   [American Solar Challenge on solar cars
    article](http://www.formulasun.org/education/seles9.html/)
-   [World Solar Challenge website](http://www.wsc.org.au/history.htm/)
-   [North American Solar
    Challenge](http://www.americansolarchallenge.org/event/asc2005/index.html/)
-   [International Solar Car A -
    Z](http://www.speedace.info/solar_cars.htm)
-   [Venturi electro-solar
    hybrid](http://www.venturi.fr/index.php?article221)
-   [A practical solar
    vehicle.](http://www.cruisecarinc.com/solar-energy.htm)

[1] Solar Vehicle Performance, Dr. Eric Slimko, December 1, 1991

[2] The Leading Edge, Tamai, Goro, Robert Bently, Inc., 1999, p. 137

[3] [The first commercial solar-electric hybrid
car](http://www.gadgetell.com/2006/10/the-first-commercial-solar-electric-hybrid-car/)
