# Dataset information


## route246

### 名前の由来

国道246号線が主な道だから。

## Variables

* date: yyyy-mm-dd style (Time)
* day: (Category... 7 variables)
* holiday: (Category... binary)
    * 0: Weekday; 1: Holiday
* *time*: time of departure. hh:mm (Time)
    * time.depart
    * time.arrive
* weather: (Category)
* to: is not **from** (Category)
    * Home or Laboratory
* route: (Category)
* traffic.lights... stop light counter (Numeric... integer)
* construction... (Numeric... integer)
* accident... (Numeric... integer)
* congestion... (Category... binary)
    * 0: No; 1: Yes
* fuel... (Category... 4 variables)
    * full, quantity, bit, empty
* tire... (Category)
* audio... (Category)
* ac... air conditioner (Category... binary)
* condition... (Category)