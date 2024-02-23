**Operating System project for OS course**

Implementation choices:
  Client side:
  - Seats can only be booked in a rightward direction, starting from a designated seat
    
  Server side:
  - Storage must be in the 'storage' folder and must be at the same level as the folder containing the compiled code

Hall:
  6 -> Rows
  12 -> Seats per row
  xxxxxoxxxxxx -> Layout of the theater hall
  ooooxooooooo -> Seat availability in the hall
  oooxxooooooo -> Seat availability in the hall
  ooooooxxxooo -> Seat availability in the hall
  oooooooooooo -> Seat availability in the hall
  oooooooooooo -> Seat availability in the hall
  xxxx=a1-3 -> Reserved seats
  xxxx=e5-1 -> Reserved seats
  xxxx=e10-1 -> Reserved seats
  xxxx=c4-2 -> Reserved seats
  xxxx=d7-3 -> Reserved seats

  Reservation Code Structure:
      yyyyMMddhhmmccxxxx -> yyyy/mm/dd date, hh:mm showtime, xxxx unique code
