# BOSS
Building Operation Smart System
BIM 7D software fro Facility Management 
1. Facility Management
2. Monitoring building behavior
3. Maintenace 
4. Bulding easy control
5. Energy Saving 

## Δ.By


| `Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|All	 	  	| `Δ.By.All()`      		| Gets all building elements 	|
|Category	  	| `Δ.By.Category(param)`   	| Gets specific element categories   	| `Windows,Doors`			|
|Type	  		| `Δ.By.Type(param)`   		| Gets specific element types   		| `Basic Walls`,`Curtain Walls`|
|Family	  		| `Δ.By.Family(param)`   	| Gets specific element families   		| `30cm Concrete`|
|Id	  			| `Δ.By.Id(param)`   		| Gets elements with specific Ids    	| `677763`|
|TypeId	  		| `Δ.By.TypeId(param)`   	| Gets elements with specific type Ids   	|`687764`|
|GUID	  		| `Δ.By.GUID(param)`   		| Gets elements with specific GUIDs     	|`1Fi$QD3af91OzrSrmvLvXA`|
|Mark	  		| `Δ.By.Mark(param)`   		| Gets elements with specific Type GUIDs   	|`1Fi$QD3af91OzrSrmvLuqy`|

#### Δ.By.Type

|`Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|Type 	  	| `Δ.By.Type(param)`    		| Gets all building elements 	|`{Area:[20,30],Volume:[5,6]}`
|Name	  		| `Δ.By.Type.Name(param)`   	| Gets specific element categories   	| `2 m`			|
|TypeMark	  		| `Δ.By.Type.TypeMark(param)`   		| Gets specific element types   		| `20 m2`	|
|TypeGUID	  		| `Δ.By.Type.TypeGUID(param)`   	| Gets specific element families   		| `4 m3`|
|TypeId	  		| `Δ.By.Type.TypeId(param)`   		| Gets elements with specific Ids    	| `300 cm`|
|OmniClass	  	| `Δ.By.Type.OmniClass(param)` 		| Gets elements with specific Ids    	| `4200 mm`|
|Category	  	| `Δ.By.Type.Category(param)`   	| Gets specific element categories   	| `Windows,Doors`	|
|Family	  		| `Δ.By.Type.Family(param)`   	| Gets specific element families   		| `30cm Concrete`|


#### Δ.By.Quantity

|`Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|Quantity 	  	| `Δ.By.Quantity(param)`    		| Gets all building elements 	|`{Area:[20,30],Volume:[5,6]}`
|Length	  		| `Δ.By.Quantity.Length(param)`   	| Gets specific element categories   	| `2 m`			|
|Area	  		| `Δ.By.Quantity.Area(param)`   		| Gets specific element types   		| `20 m2`	|
|Volume	  		| `Δ.By.Quantity.Volume(param)`   	| Gets specific element families   		| `4 m3`|
|Width	  		| `Δ.By.Quantity.Width(param)`   		| Gets elements with specific Ids    	| `300 cm`|
|Perimeter	  	| `Δ.By.Quantity.Perimeter(param)` 		| Gets elements with specific Ids    	| `4200 mm`|

#### Δ.By.Space
| `Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|Space 	  	| `Δ.By.Space(param)`    				| Gets all building elements 	|`{Area:[20,30],Volume:[5,6]}`
|Id	  		| `Δ.By.Space.Id(param)`   				| Gets specific element categories   	| `348984`			|
|No	  		| `Δ.By.Space.No(param)`   				| Gets specific element types   		| `205`	|
|Name	  		| `Δ.By.Space.Name(param)`   		| Gets specific element families   		| `Corridor`|
|Zone	  		| `Δ.By.Space.Zone(param)`   		| Gets elements with specific Ids    	| `Official`|
|Occupancy	  	| `Δ.By.Space.Occupancy(param)`   	| Gets specific element categories   	| `Circulation`	|		
|Occupant	  	| `Δ.By.Space.Occupant(param)`  | Gets specific element types   			| `40`			|
|Department	  	| `Δ.By.Space.Department(param)`   		| Gets specific element families   	| `Educational`|
|Room	  		| `Δ.By.Space.Room(param)`   		| Gets elements with specific Ids    	| `Bedroom`	|
|RoomNo  		| `Δ.By.Space.RoomNo(param)`   		| Gets elements with specific Ids    	| `205`		|
|RoomId	  		| `Δ.By.Space.RoomId(param)`   		| Gets elements with specific Ids    	| `538389`	|
|Height	  		| `Δ.By.Space.Height(param)`   		| Gets specific element families   		| `3 m`		|
|Area	  		| `Δ.By.Space.Area(param)`   		| Gets elements with specific Ids    	| `24 m2`	|
|Perimeter  	| `Δ.By.Space.Perimeter(param)`   		| Gets elements with specific Ids   | `45 m`|
|Volume	  		| `Δ.By.Space.Volume(param)`   		| Gets elements with specific Ids    	| `5 m3`|

#### Δ.By.Quantity

|`Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|Quantity 	  	| `Δ.By.Quantity(param)`    		| Gets all building elements 	|`{Area:[20,30],Volume:[5,6]}`
|Length	  		| `Δ.By.Quantity.Length(param)`   	| Gets specific element categories   	| `2 m`			|
|Area	  		| `Δ.By.Quantity.Area(param)`   		| Gets specific element types   		| `20 m2`	|
|Volume	  		| `Δ.By.Quantity.Volume(param)`   	| Gets specific element families   		| `4 m3`|
|Width	  		| `Δ.By.Quantity.Width(param)`   		| Gets elements with specific Ids    	| `300 cm`|
|Perimeter	  	| `Δ.By.Quantity.Perimeter(param)` 		| Gets elements with specific Ids    	| `4200 mm`|

#### Δ.By.System

|`Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|System 	  	| `Δ.System(param)`    		| Gets all building elements 	|`{Area:[20,30],Volume:[5,6]}`
|Name	  		| `Δ.By.System.Name(param)`   	| Gets specific element categories   	| `2 m`			|
|Type	  		| `Δ.By.System.Type(param)`   		| Gets specific element types   		| `20 m2`	|
|Classification	| `Δ.By.System.Classification(param)` | Gets specific element types   		| `20 m2`	|
