# Baseball-Career-sim-3
print("   *** Jameson Kinsky ***")
print("")
print("    ++++ PRESENTS ++++")
print("")
print("[][]      []    [][][]  [][][]        ")
print("[]  []  []  []  []      []   ")
print("[][]    [][][]  [][][]  [][][]         ")
print("[]  []  []  []      []  []         ")
print("[][]    []  []  [][][]  [][][]         ")
print("")
print("[][]      []    []      []              ")
print("[]  []  []  []  []      []             ")
print("[][]    [][][]  []      []             ")
print("[]  []  []  []  []      []             ")
print("[][]    []  []  [][][]  [][][]               ")
print("")
print("     <<< CAREER SIM >>>")
print("")
print("             3")
print("")
print("      ***Directions***")
print("")
print("- To advance a season press *ENTER*") 
print("- To retire press *3*") 
print("- To play normaly just enter you players name and click enter")
print("- To see the player catolag type number *1* at the first question. When you want to choose your player type the corresponding number EX: Yogi Berra type 1.")
Ch=0
C2b=0
C3b=0
Cbb=0
C1b=0
Chr=0
Csb=0
Cab=0
Cba=0
Cobp=0
Cslg=0
Cops=0
Cwar=0
Copsplus=0
Cgain=0
HRgain=0
SBgain=0
Vgain=0
XBHgain=0
season=1
Cmoney=0
Team=0
MVP=0
SS=0
AS=0
import random
randomContractL=random.randint(1,5)
randomContractM=random.randint(1.000000,5.000000)
ContractL=randomContractL
ContractM=randomContractM
Name=input("What is your players name? ")
print("")
Vision=random.randint(10,85)
print((Name) + "'s vision: " + str(Vision) + "/100")
Contact=random.randint(10,85)
print((Name) + "'s Contact: " + str(Contact) + "/100")
HRpower=random.randint(10,85)
print((Name) + "'s HRpower: " + str(HRpower) + "/100")
XBHpower=random.randint(10,85)
print((Name) + "'s XBHpower: " + str(XBHpower) + "/100")
SBpower=random.randint(1,85)
print((Name) + "'s SBpower: " + str(SBpower) + "/100")
Age=random.randint(18,22)
print((Name) + "'s Age: " + str(Age))
draft=random.randint(1,7)
if Name=="1":
  print("")
  print("         *** PLAYER CATALOG ***")
  print("")
  print("                       V   C   HR  XBH  SB  A")
  print("             *** HOF C ***")
  print("1 - Yogi Berra         75  85  70  65   5   21")
  print("2 - Gary Carter        60  70  80  70   10  20")
  print("3 - Mike Piazaa        55  90  85  65   10  23")
  print("4 - Ted Simmons        75  85  70  85   10  19")
  print("5 - Carlton Fisk       60  65  70  75   15  21")
  print("6 - *JOHNNY BENCH*     65  80  80  70   15  19")
  print("             *** HOF 1B ***")
  print("7 - Dan Brouthers      100 105 10  85   45  21")
  print("8 - Jimmie Foxx         75 100 95  85   10  17")
  print("9 - Eddie Murray        65  85 95  100  35  21")
  print("10 - Frank Thomas       60  95 105 95   10  22")
  print("11 - Jim Thome          55  75 115 80    5  21")
  print("12 - *LOU GEHRIG*       95 115 95  100  35  19")
  print("13 - David Ortiz        55  85 105 105  10  21")
  print("              *** HOF 2B ***")
  print("14 - Joe Morgan         100 80 55  80   110 20")
  print("15 - Jackie Robinson    95 105 55  80   80  28")
  print("16 - Ryne Sandberg      50  80 80  75   80  21")
  print("17 - *ROGERS HORNSBY*   95 115 75  90   55  19")
  print("              *** HOF 3B ***")
  print("18 - Wade Boggs         85 105 45   90  5   23")
  print("19 - George Brett       70 105 70  105  55  20")
  print("20 - Chipper Jones      70  95 90   95  45  21")
  print("21 - Eddie Mathews      50  75 105  85  30  20")
  print("22 - *MIKE SCHMIDT*     55  80 110  90  50  22")
  print("")
  print("                        V   C   HR  XBH  SB  A")
  print("              *** HOF SS ***")
  print("23 - Ernie Banks        65  75  95   55  15 22")
  print("24 - Derek Jeter        50  100 70   95  90 20")
  print("25 - Barry Larkin       80  90  20   90  50 22")
  print("26 - Cal Ripken Jr      65  80  80   90  10 20")
  print("27 - Robin Yount        45  80  55   90  85 18")  
  print("                  ???")
  print("28 - Barry Bonds        115 105 125  115 95 21")
  print("29 - I**K A***R         95  105 125 115 125 18")
  print("30 - *CHARLIE MADDEN*   125 125 125 125 125 18")
  print("31 - Joe Stoshak         85 105 105 95  100 18")
  print("32 - D***K S***S        55  75  135 125  55 18")
  print("33 - Tony F Pena III    10  125 125 125 125 18")
  print("")
  print("")
  print("")
  whatplayer=input(" What player? ")
  if whatplayer=="1":
    Vision=75
    Contact=85
    HRpower=70
    XBHpower=65
    SBpower=5
    Age=21
    Name="Yogi Berra"
  if whatplayer=="2":
    Vision=60
    Contact=70
    HRpower=80
    XBHpower=70
    SBpower=10
    Age=20
    Name="Gary Carter"
  if whatplayer=="3":
    Vision=55
    Contact=90
    HRpower=85
    XBHpower=65
    SBpower=10
    Age=23
    Name="Mike Piazaa"
  if whatplayer=="4":
    Vision=75
    Contact=85
    HRpower=70
    XBHpower=85
    SBpower=10
    Age=19
    Name="Ted Simmons"

  if whatplayer=="5":
    Vision=60
    Contact=65
    HRpower=75
    XBHpower=75
    SBpower=15
    Age=21
    Name="Carlton Fisk"
  if whatplayer=="6":
    Vision=65
    Contact=80
    HRpower=80
    XBHpower=70
    SBpower=15
    Age=19
    Name="Johnny Bench"

  
  if whatplayer=="7":
    Vision=100
    Contact=105
    HRpower=10
    XBHpower=85
    SBpower=45
    Age=21
    Name="Dan Brouthers"
  if whatplayer=="8":
    Vision=75
    Contact=100
    HRpower=95
    XBHpower=85
    SBpower=10
    Age=17
    Name="Jimmie Foxx"
  if whatplayer=="9":
    Vision=65
    Contact=85
    HRpower=95
    XBHpower=100
    SBpower=35
    Age=21
    Name="Eddie Murray"
  if whatplayer=="10":
    Vision=60
    Contact=95
    HRpower=105
    XBHpower=95
    SBpower=10
    Age=22
    Name="Frank Thomas"

  if whatplayer=="11":
    Vision=55
    Contact=75
    HRpower=115
    XBHpower=80
    SBpower=5
    Age=21
    Name="Jim Thome"
  if whatplayer=="12":
    Vision=95
    Contact=115
    HRpower=95
    XBHpower=100
    SBpower=35
    Age=19
    Name="Lou Gehrig"
  if whatplayer=="13":
    Vision=55
    Contact=85
    HRpower=105
    XBHpower=105
    SBpower=10
    Age=21
    Name="David Ortiz"
  if whatplayer=="14":
    Vision=100
    Contact=80
    HRpower=55
    XBHpower=80
    SBpower=110
    Age=20
    Name="Joe Morgan"
  if whatplayer=="15":
    Vision=95
    Contact=105
    HRpower=55
    XBHpower=80
    SBpower=80
    Age=28
    Name="Jackie Robinson"
  if whatplayer=="16":
    Vision=50
    Contact=80
    HRpower=80
    XBHpower=75
    SBpower=80
    Age=21
    Name="Ryne Sandburg"
  if whatplayer=="17":
    Vision=95
    Contact=115
    HRpower=75
    XBHpower=90
    SBpower=55
    Age=19
    Name="Rogers Hornsby"
  if whatplayer=="18":
    Vision=85
    Contact=105
    HRpower=45
    XBHpower=90
    SBpower=5
    Age=23
    Name="Wade Boggs"
  if whatplayer=="19":
    Vision=70
    Contact=105
    HRpower=70
    XBHpower=105
    SBpower=55
    Age=20
    Name="George Brett"
  if whatplayer=="20":
    Vision=70
    Contact=95
    HRpower=90
    XBHpower=95
    SBpower=45
    Age=21
    Name="Chipper Jones"
  if whatplayer=="21":
    Vision=50
    Contact=75
    HRpower=105
    XBHpower=85
    SBpower=30
    Age=20
    Name="Eddie Mathews"
  
  if whatplayer=="22":
    Vision=55
    Contact=80
    HRpower=110
    XBHpower=90
    SBpower=50
    Age=22
    Name="Mike Schmidt"


  
  if whatplayer=="23":
    Vision=65
    Contact=75
    HRpower=95
    XBHpower=55
    SBpower=15
    Age=22
    Name="Ernie Banks"
  
  if whatplayer=="24":
    Vision=50
    Contact=100
    HRpower=70
    XBHpower=95
    SBpower=90
    Age=20
    Name="Derek Jeter"
  if whatplayer=="25":
    Vision=80
    Contact=90
    HRpower=20
    XBHpower=90
    SBpower=50
    Age=22
    Name="Barry Larkin"
  if whatplayer=="26":
    Vision=65
    Contact=80
    HRpower=80
    XBHpower=90
    SBpower=10
    Age=20
    Name="Cal Ripken JR"
  if whatplayer=="27":
    Vision=45
    Contact=80
    HRpower=55
    XBHpower=90
    SBpower=85
    Age=18
    Name="Robin Yount"
  if whatplayer=="28":
    Vision=115
    Contact=105
    HRpower=125
    XBHpower=115
    SBpower=95
    Age=21
    Name="Barry Bonds"
  if whatplayer=="29":
    Vision=95
    Contact=105
    HRpower=125
    XBHpower=115
    SBpower=125
    Age=18
    Name="I**K A***R"
  if whatplayer=="30":
    Vision=125
    Contact=125
    HRpower=125
    XBHpower=125
    SBpower=125
    Age=18
    Name="Charlie Madden"
  if whatplayer=="31":
    Vision=85
    Contact=105
    HRpower=105
    XBHpower=95
    SBpower=100
    Age=18
    Name="Joe Stoshak"
  print("")
  print("")
print("")
print((Name) + " was drafted in the: " + str(draft) + " round")
print("")
Team=random.randint(1,30)
if Team==1:
  Team = "Baltimore Orioles"
  print("Team : Baltimore Orioles")
if Team==2:
  Team = "Boston Red Sox"
  print("Team : Boston Red Sox")
if Team==3:
  Team = "New York Yankees"
  print("Team : New York Yankees")
if Team==4:
  Team = "Tampa bay Rays"
  print("Team : Baltimore Orioles")
if Team==5:
  Team = "Toronto Blue Jays"
  print("Team : Torontro Blue Jays")

  
if Team==6:
  Team = "Chicago White Sox"
  print("Team : Chicago White Sox")
if Team==7:
  Team = "Clevland Indians"
  print("Team : Cleveland Indians")
if Team==8:
  Team = "Detroit Tigers"
  print("Team : Detroit Tigers")
if Team==9:
  Team = "Kansas City Royals"
  print("Team : Kansas City Royals")
if Team==10:
  Team = "Minnesota Twins"
  print("Team : Minnesota Twins")
if Team==11:
  Team = "Houston Astros"
  print("Team : Houston Astros")
if Team==12:
  Team = "Los Angeles Angels of Anaheim"
  print("Team : Loas Angeles Angels of Anaheim")
if Team==13:
  Team = "Oakland Athletics"
  print("Team : Oakland Athletics")
if Team==14:
  Team = "Seatle Mariners"
  print("Team : Seatle Mariners")
if Team==15:
  Team = "Texas Rangers"
  print("Team : TEXAS RANGERS")

if Team==16:
  Team = "Alanta Braves"
  print("Team : Alanta Braves")
if Team==17:
  Team = "Miami Marlins"
  print("Team : Miami Marlins")
if Team==18:
  Team = "New York Mets"
  print("Team : New York Mets")
if Team==19:
  Team = "Philadelphia Phillies"
  print("Team : Philadelphia Phillies")
if Team==20:
  Team = "Washington Nationals"
  print("Team : Washinton Nationals")

  

if Team==21:
  Team = "ST Louis Cardinals"
  print("Team : ST Louis Cardinals")
if Team==22:
  Team = "Chicago Cubs"
  print("Team : Chicago Cubs")
if Team==23:
  Team = "Pittsburg Pirates"
  print("Team : Pittsburg Pirates")
if Team==24:
  Team = "Milwaukee Brewers"
  print("Team : Milwaukee Brewers")
if Team==25:
  Team = "Cincinati Reds"
  print("Team : Cincinati Reds")


  
if Team==26:
  Team = "San Francisco Giants"
  print("Team : San Francisco Giants")
if Team==27:
  Team = "Arizona Diamondbacks"
  print("Team : Arizona Diamondbacks")
if Team==28:
  Team = "Los Angeles Dodgers"
  print("Team : Los Angeles Dodgers")
if Team==29:
  Team = "San Deigo Padres"
  print("Team : San Deigo Padres")
if Team==30:
  Team = "Colorado Rockies"
  print("Team : Colorado Rockies")

print("")
print("The " + (Team) + " signed you to a " + str(ContractL) + " year " + str(ContractM) + " million doller contract.")
import time
while True:
  print("")
  start=input("Start Season? ")
  if start=="3":
    break
  print("")
  time.sleep(.33)
  print("")
  time.sleep(.33)
  print("")
  time.sleep(.33) 
  print("___________________________________________________")
  print(" ***Season number " + str(season) + "***")
  print("___________________________________________________")
  print("AGE: " + str(Age))
  print("")
  print(Name + "'s attributes:")
  print("Vision: " + str(Vision) + "/100" + " / Contact: " + str(Contact) + "/100")
  print("HRpower: " + str(HRpower) + "/100" + " / XBHpower: " + str(XBHpower) + "/100")
  print("SBpower: " + str(SBpower) + "/100")
  print("")
  gamesplayed=random.randint(135,162)
  pa=(gamesplayed*4)
  walkrate=(Vision/7.68)
  randomBB=random.randint(-5,5)
  BB=(pa*(walkrate/85)+randomBB)
  ab=(pa-BB)
  random1b=random.randint(-8,15)
  Singles=(((Contact/450)*ab)+random1b)
  randomhits=random.randint(-8,10)
  hits=(((Contact/300)*ab)+randomhits)
  BA=(hits/ab) 
  Random2b=random.randint(-7,7)
  doubles=((ab*.3)*(XBHpower/350)+Random2b)
  Randomtriple=random.randint(-2,1)
  triple=((ab*.2)*(XBHpower/1500)+Randomtriple)
  obp=((hits+BB)/(ab+BB))
  RandomHR=random.randint(-5,5)
  HR=(((ab*.3)*(HRpower/350))+RandomHR)
  slg=((Singles+(doubles*2)+(triple*3)+(HR*4))/ab)
  ops=(obp+slg)
  Randomsb=random.randint(-8,8)
  SB=((ab*.3)*(SBpower/200)+Randomsb)
  WAR=((((BA+obp+slg)*4.7)))
  OPS_plus=(100*((obp/.320)+(slg/.415)-1))
  if 0 > Contact:
      Contact=0
  if 0 > HRpower:
      HRpower=0
  if 0 > Vision:
      Vision=0
  if 0 > XBHpower:
      XBHpower=0
  if 0 > SBpower:
      SBpower=0
      
  if 0 > Singles:
      Singles=0
  if 0 > doubles:
        doubles=0
  if 0 > triple:
      triple=0
  if 0 > BA:
      BA=0
  if 0 > BB:
      BB=0
        
  if 0 > hits:
      hits=0
  if 0 > HR:
      HR=0
  if 0 > SB:
      SB=0
   
      
      
   
  print("")
  print(Name + "'s season stats are: ")
  print("")
  print("G    BB   1B  2B  3B  HR  SB   H ")
  print(str(gamesplayed) + "  " + str(round(BB)) + "   " + str(round(Singles)) + "  " + str(round(doubles)) + "  " + str(round(triple)) + "  " + str(round(HR)) + "  " + str(round(SB)) + "  " + str(round(hits)))
  print("BA   OBP    SLG   OPS   OPS+  WAR")
  print(str(round(BA,3)) + " " + str(round(obp,3)) + " " + str(round(slg,3)) + " " + str(round(ops,3)) + " " + str(round(OPS_plus)) + "   " + str(round(WAR,2)))
  
    
  if Age < 24:
      Cgain=random.randint(1,7)
      HRgain=random.randint(1,7)
      SBgain=random.randint(1,7)
      Vgain=random.randint(1,7)
      XBHgain=random.randint(1,7)
  if Age > 23 and Age < 29:
      Cgain=random.randint(1,3)
      HRgain=random.randint(1,3)
      SBgain=random.randint(1,3)
      Vgain=random.randint(1,3)
      XBHgain=random.randint(1,3)
  if Age > 29:
      Cgain=random.randint(-8,-2)
      SBgain=random.randint(-8,-2)
      Vgain=random.randint(-8,-2)
      XBHgain=random.randint(-8,-2)
      HRgain=random.randint(-8,-2)
  if Age > 37:
      Cgain=random.randint(-10,-3)
      HRgain=random.randint(-10,-3)
      SBgain=random.randint(-10,-3)
      Vgain=random.randint(-10,-3)
      XBHgain=random.randint(-10,-3)
  if Age > 42:
      Vgain=random.randint(-15,-5)
      SBgain=random.randint(-15,-5)
      HRgain=random.randint(-15,-5)
      Cgain=random.randint(-15,-5)
      XBHgain=random.randint(-15,-5)
  
    
  print("")
  print(Name + "'s off season gains")
  print("")
  print("Contact gain " + str(Cgain) + " / HRpower gain " + str(HRgain))
  print("SBpower gain " + str(SBgain) + " / Vision gain " + str(Vgain))
  print("XBHpower gain " + str(XBHgain))
  
  Contact=(Contact+Cgain)
  HRpower=(HRpower+HRgain)
  SBpower=(SBpower+SBgain)
  Vision=(Vision+Vgain)
  XBHpower=(XBHpower+XBHgain)
                              
  print("")
  print("Career stats:")
  print("")
  Ch=(Ch+hits)
  print("H   : " + str(round(Ch)))
  C2b=(C2b+doubles)
  print("2B  : " + str(round(C2b)))
  C3b=(C3b+triple)
  print("3B  : " + str(round(C3b)))
  Cbb=(Cbb+BB)
  print("BB  : " + str(round(Cbb)))
  C1b=(C1b+Singles)
  print("1B  : " + str(round(C1b)))
  Cab=(Cab+ab)
  Csb=(Csb+SB)
  print("SB  : " + str(round(Csb)))
  Chr = HR + Chr
  print("HR  : " + str(round(Chr)))
  Cba=(Ch/Cab)
  print("BA  : " + str(round(Cba,3)))
  Cobp=((Ch+Cbb)/(Cab+Cbb))
  print("OBP : " + str(round(Cobp,3)))
  Cslg=((C1b+(C2b*2)+(C3b*3)+(Chr*4))/Cab)
  print("SLG : " + str(round(Cslg,3)))
  Cops=(Cobp+Cslg)
  print("OPS : " + str(round(Cops,3)))
  Cwar=(Cwar+WAR)
  print("WAR : " + str(round(Cwar,2)))
  Copsplus=((((Cobp/.320)+(Cslg/.415))-1)*100)
  print("OPS+: " + str(round(Copsplus)))
  print("")
  print("            ---AWARDS---")
  if OPS_plus > 165 and WAR > 7:
    print("   **** YOU WON THE MVP AWARD ****")
    MVP=MVP+1
  if OPS_plus > 135 and WAR > 5 and BA > .250:
    print("   **** YOU WON THE SS AWARD ****")
    SS=SS+1
  if OPS_plus > 125 and BA > .250 and HR > 20:
    print("   **** YOU ARE AN ALL STAR ****")
    AS=AS+1
  if OPS_plus < 115 and BA <.250 and HR < 20:
    print("       No awards")
  
  print("")
  Cmoney=Cmoney + (ContractM/ContractL)
  print("")
  print("   **** END OF SEASON " + str(season) + " ****") 
  print("")
  print(" --->  SCROLL UP TO SEE SEASON STATS  <---")
  print("")
  season=season+1

      
  Age=Age+1
  ContractL=ContractL-1
  
  if ContractL==0:
    randomContractL=random.randint(1,10)
    ContractL=randomContractL
    ContractM=((WAR*4.2)*(ContractL))
    Team=random.randint(1,30)
    if Team==1:
        Team = "Baltimore Orioles"
       
    if Team==2:
        Team = "Boston Red Sox"
        
    if Team==3:
        Team = "New York Yankees"
       
    if Team==4:
        Team = "Tampa bay Rays"
       
    if Team==5:
        Team = "Toronto Blue Jays"
      
      
        
    if Team==6:
        Team = "Chicago White Sox"
       
    if Team==7:
        Team = "Clevland Indians"
        
    if Team==8:
        Team = "Detroit Tigers"
        
    if Team==9:
        Team = "Kansas City Royals"
      
    if Team==10:
        Team = "Minnesota Twins"
        
    if Team==11:
        Team = "Houston Astros"
       
    if Team==12:
        Team = "Los Angeles Angels of Anaheim"
      
    if Team==13:
        Team = "Oakland Athletics"
       
    if Team==14:
        Team = "Seatle Mariners"
        
    if Team==15:
        Team = "Texas Rangers"
       
      
    if Team==16:
        Team = "Alanta Braves"
        
    if Team==17:
        Team = "Miami Marlins"
       
    if Team==18:
        Team = "New York Mets"
      
    if Team==19:
        Team = "Philadelphia Phillies"
        
    if Team==20:
        Team = "Washington Nationals"
      
    if Team==21:
        Team = "ST Louis Cardinals"
      
    if Team==22:
        Team = "Chicago Cubs"
       
    if Team==23:
        Team = "Pittsburg Pirates"
        
    if Team==24:
        Team = "Milwaukee Brewers"
        
    if Team==25:
        Team = "Cincinati Reds"
    if Team==26:
        Team = "San Francisco Giants"
        
    if Team==27:
        Team = "Arizona Diamondbacks"
        
    if Team==28:
        Team = "Los Angeles Dodgers"
    if Team==29:
        Team = "San Deigo Padres"
        
    if Team==30:
        Team = "Colorado Rockies"
        
      

      
    print("")
    print("   *** CONTRACT UPDATE ***")
    round(ContractM,3)
    print("The " + (Team) + " signed you to a " + str(ContractL) + " year " + str(ContractM) + " million doller contract.")
print("")
print("___________________________________________________")
print("   *** CAREER OVER ***")
print("")
print("SEASONS PLAYED : " + str(season))
print("")
print("   *** MONEY MADE ***")
print("")
round(Cmoney,3)
print(str(Cmoney) + " Million dollers")
print("")
print("   *** AWARDS ***")
print("")
print("All star games : " + str(AS))
print("MVPs           : " + str(MVP))
print("Silver Slugers : " + str(SS))
print("")

print("")
if season > 10 and Cwar > 85 and Chr > 350 and Ch > 2000 and Copsplus > 135:
  print("   +++ HALL OF FAME +++")
