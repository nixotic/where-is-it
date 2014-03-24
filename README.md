where-is-it
===========

A database of things. This is currently just an idea.

The primary intended function is to be able to track electronic components and related info, but why stop with components?

### Ideas

  * Database uses a format that lends itself to being version controlled (eg via git)
    * Eg. Text based (maybe even human readable? YAML?)
  * Coding to be done as much as possible in python
  * Open front end interface (eg. JSON) 
    * The back end tracking/DB system shouldn't be tied to a GUI/front-end

### Example Component Info
  * Short name (eg 10K Resistor)
  * Description (Resistor, 10K Ohm, 1/8 Watt, Surface Mount)
  * Footprint name (SMD0805)
  * Footprint data (link to, or capture of gEDA/pcb footprint file/text)
  * Component specific data (this requires definition of some component types etc)
    * Type: Resistor
    * Resistance: 10K Ohm
    * Power: 1/8 Watt
    * Mounting: Surface Mount
    * Footprint: 0805 (or perhaps link to the above data)
    * Symbol info (for schematic layout)
    * Simulation info (for SPICE analysis - may include actual subcircuit/file/text?)
    * Manufacturer/s: Yageo, ???
    * Maunfacturers P/N: xxx, yyy
    * Suppliers: Element14, RS Components, Digikey
    * Supplier P/Ns: xxx, yyy, nnn
    * Costs ...

Not every thing will have detailed info. The flexibility to neither require too much information or limit how much can
included is important. It would also be good be able to avoid duplicated components...
