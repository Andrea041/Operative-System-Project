**Operating System project for OS course**

Implementation choices:
  Client side:
  - Seats can only be booked in a rightward direction, starting from a designated seat
    
  Server side:
  - Storage must be in the 'storage' folder and must be at the same level as the folder containing the compiled code
    
    File sala:
        6 -> File
        12 -> Posti
        xxxxxoxxxxxx -> Sala
        ooooxooooooo -> Sala
        oooxxooooooo -> Sala
        ooooooxxxooo -> Sala
        oooooooooooo -> Sala
        oooooooooooo -> Sala
        xxxx=a1-3
        xxxx=e5-1
        xxxx=e10-1
        xxxx=c4-2
        xxxx=d7-3

        Struttura codice prenotazioni:
            dataoracodiceunivoco
            aaaammddhhmmccxxxx -> aaaa/mm/dd data, hh:mm orario spettacolo, xxxx codice univoco
