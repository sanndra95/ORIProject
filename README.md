# ORIProject
Projekat iz predmeta Osnovi racunarske inteligencije
Tema projekta: Detekcija emocija na ljudskom licu
Treniranje i evaluacija se vrsi pokretanjem neural_network.py fajla, a pokretanje samog projekta sa GUI konzolom radi testiranja sopstvenih slika se vrsi pokretanjem main.py fajla.
U projektu su trenirana dva modela, jedan sa 4 emocije (happy, sad, angry, neutral) i model je sacuvan u model.h5 fajlu, i drugi sa 3 emocije (happy, angry, neutral) koji je sacuvan u model_ws.h5 fajlu. Drugi model je napravljen jer smo u datasetu imale premalo podataka za emociju sad, i procenat detekcije te emocije nije bio zadovoljavajuci.
Projekat se moze pokrenuti sa oba modela, pri cemu ako zelimo da ukljucimo emociju sad, treba promeniti boolean SAD_MODE iz neural_network.py na False i NUM_OF_CLASSES na 4 umesto 3.
Da bi se izvrsilo ponovno treniranje modela, potrebno je izbrisati model.h5 i model_ws.h5 fajlove i promeniti boolean TRAINING iz neural_network.py na True.
