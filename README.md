---
marp: true
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---
<center>

<h1> Analiza wypadków drogowych w Wielkiej Brytanii <br> w latach 2005-2015
<h3> Antoni Zajko

---
<center> <h2> Zbior danych <br></center>

<a href="https://www.kaggle.com/silicon99/dft-accident-data">
UK Car Accidents 2005-2015
</a> <br>
Zbiór zawiera informacje dotyczące około 1,8 mln wypadków drogowych. <br>
Oprócz danych dotyczących samych wypadków są także dane dotyczące pojazdów, a także ofiar.

---
<center><h1> Użyte narzędzia</h1></center> 
<li> Python
<li> Pandas
<li> Matplotlib
<li> Seaborn

---
<h1>Jakie manewry na drodze są najbardziej ryzykowne?</h1>
<center>
<img src="plots/accidents_by_maneouvre.png">
</center>
Największa szansa na wypadek jest podczas skręcania. Wynika to najpewniej z tego, że ten manewr wykonujemy najczęsciej, oraz bardzo łatwo jest podczas niego wymusić pierszeństwo, co jest jedną z najczęstszych przyczyn wypadków na drodze.

---
<center>
<h1> Czy pojazd, którym się poruszamy ma wpływ na śmiertleność podczas wypadku?
</center>
<center>
<img src='plots/fatals_by_vehicle_type.png', width=419, height=326>
<img src='plots/accidents_by_vehicle_type.png', width=419, height=326>
</center>
Z wykresu wynika, że największa szansa na śmierć podczas wypadku jest podczas jazdy tramwajem. Warto też zwrócić na wysoką śmiertelność wypadków podczas jazdy motocyklem.

---
<center><h1> Uderzenie z której strony w pojazd jest najbardziej śmiertelne?</h1></center>
<center>
<img src='plots/fatals_by_impact_side.jpeg', width=600>
<img src='plots/car_img.jpg'>
</center>

---
<center><h1> Skuteczność kampanii działających przeciwko wypadkom

---
<center>
<h1> Ogólny trend w ilości wypadków
<img src = "plots/accidents_timeline_annual.jpeg", height = 450>

---
<center>
<h1> Porównanie lat z kampanią i bez kampanii
<center>
<img src = "plots/accidents_monthly_comparision.png", height = 350>

---
<center>
<h1>Dziękuje za obejrzenie prezentacji
<h3>Antoni Zajko