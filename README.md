# Operating System project for OS course

Implementation choices:
  Client side: 
  - Seats can only be booked in a rightward direction, starting from a designated seat
    
  Server side:
  - Storage must be in the 'storage' folder and must be at the same level as the folder containing the compiled code

### Hall Configuration:
- Rows: 6
- Seats per Row: 12

#### Layout of the Theater Hall:
xxxxxoxxxxxx  

#### Seat Availability in the Hall:
ooooooxxxxoo  
oxoooooxoooo  
oooooooxoooo  
oooooooooooo  
oooooooooooo  
oooooooooooo  

#### Reserved Seats:
- xxxx=a1-3
- xxxx=e5-1
- xxxx=e10-1
- xxxx=c4-2
- xxxx=d7-3

### Reservation Code Structure:
yyyyMMddhhmmccxxxx -> yyyy/mm/dd date, hh:mm showtime, xxxx unique code
