# JS & JQuery
## Creating an object with constructor notation
```js
const hotel = new Object(); /

hotel.name = 'Quay';
hotel.rooms = 40;
hotel.booked = 25;

hotel.checkAvailability = function () {
    return this.room - this.booked;
}
```

## creating multiple objects w/ constructor notation
```js
function Hotel(name, rooms, booked) {

this.name = name;
this.rooms = rooms;
this.booked = booked;
this.checkAvailability = function() {
    return this.rooms - this.booked;
}
}

const quayHotel = new Hotel('Quay', 40, 25);
const park = new Hotel('Park', 120, 77);
```

# HTML & CSS
## Tables
4 main elements
1. table
2. tr
3. td
4. th 
* can split up the table using tr, tbody and tfoot. 