# Warefare Rules in Bullet Point Form

## Terms

**Unit** - a group of soldiers moving together at the command of the ruler.
**Order** - A ruler's command to for how a Unit should act each round
**Province** - a section of land
**Landmark** - a place of interest within a Province which gives some sort of benefit to the Province's current owner

## Units

- each unit has a strength score of 1
- units are split into two types:
  - Army - can move on inland and coastal provinces
  - Fleet - can move on coastal and ocean provinces
- only 1 unit is allowed in a province at any given time
- units can take Orders:
  - Move - the unit attempts to move into an adjacent province
  - Hold - the unit stays in its current province and does nothing
  - Support - the unit stays in its current province and adds its power to another unit's Move action, combining their strength scores
  - Convoy - a Fleet unit attempts to help an Army unit move across an ocean province
- the number of units for a kingdom is equal to the kingdom's Might score

## Provinces

- the entire map is divided into provinces; the game's map is like a a piece of broken glass where each shard is a province and each crack is a border.
- only one unit is allowed in a province at any given time
- provinces may sometimes contain a Landmark
- Provinces are split into two types:
  - Land - provinces on solid ground, split further into two types
    - Inland
      - a Land province adjacent only to other Land provinces
      - traversable only by Army units
    - Coastal - a Land province that shares a border with an Ocean province
      - traversable by both Army and Fleet units
  - Ocean - provinces with a body of water as their main feature, traversable only by Fleet units
- Provinces are "owned" by the kingdom who most recently had a unit occupying it
- each province has a unique label or name to identify it

## Orders

- Orders are given to units by the ruler of the kingdom to which the unit belongs
- Orders are planned during the round, but do not execute until the end of the round
- Orders may be changed as much as necessary during the round, but are locked in when the round ends
- there are four types of orders:
  - Move
    - order a unit to move into a province adjacent to the province the unit current resides in
    - Move orders are dependent on a unit's strength score
    - Resolution:
      - rulers specify which unit they are ordering to move by identifying the unit type and province label
      - after specifying the unit, the ruler indicates when adjacent province they want the unit to move into
      - if the adjacent province does not contain another unit, the unit moves into the adjacent province
      - if there is already a unit occupying the adjacent province, a strength contest is initiated to determine which unit will take control of the adjacent province, taking into account relevant Support orders
        - if the existing unit's strength score is greater than or equal to the incoming unit's strength score, neither unit moves
        - if the incoming unit's strength score is higher, the incoming unit supplants the existing unit and the existing unit must attempt to move to another adjacent province or be removed from the map
  - Support
    - order a unit to add its strength score to the strength score of another unit
    - Support orders can only be given to bolster Move or Hold orders of other units
    - Support orders can only be given for adjacent provinces that the supporting unit could have moved into, taking into account unit type and province type
    - a unit can Support any other unit, regardless of kingdom allegiance
    - units with Support orders do not move, unless forced to move by failing a strength contest with another unit's Move order
  - Hold
    - order a unit to stay in its current province
    - Hold orders can be bolstered by Support orders from other units
  - Convoy
    - order a Fleet to assist an Army unit in moving across Ocean provinces
    - Resolution:
      - rulers specify which Fleet unit they intend to use in a Convoy order by identifying the Fleet's current province label
      - after specifying the Fleet unit, the ruler indicates which Army unit it intends to move across an Ocean province by identifying the Army's current province label as well as the label of the province the ruler intends to Army to end the movement in
        - The origin and destination provinces must be Coastal provinces.
        - The origin and destination provinces must both share a border with an Ocean province which current contains the Fleet unit being issued the convoy command
    - Convoy order movements are subject to the same strength contests of Move orders
      - A convoy movement is effectively a Move order for the Army unit being convoyed, therefore it can make use of Support orders by units adjacent to the destination province

## Landmarks

- some provinces will have a Landmark
- The kingdom that owns a province also owns the Landmark in that province if one exists
- Landmarks give a variety of benefits:
  - Supply Centers - adjustments to Kingdom Resources scales
    - several per map
  - Linked Portals - allows Move orders between the provinces linked by the portals, regardless of adjacency
    - only 2 per map
  - Mercenary Company - gain access to an extra Unit
    - a few per map
  - Place of Power - free Make a Big Play writ when captured
    - only 1 per map
  - Person of Interest - autocomplete a project when captured
    - a few per map
  - Ancient Ruins - extra actions each round
    - a few per map
