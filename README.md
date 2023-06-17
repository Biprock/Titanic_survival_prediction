# Titanic_survival_prediction 🚢
Predicting the number of people who survived after Titanic Disaster using Linear Regression Model.

## Source :  <a href = "https://www.kaggle.com/competitions/titanic"> Titanic-Kaggle<a/>

<b>train.csv</b> contains the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.
<br>
<br>
The <b>test.csv</b> dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.
<br>
<br>
The <b>pred.csv</b> contains the predicted survival information.

## Dataset description
- <b>Survived: </b>The first feature reported if a traveler lived or died.<br><br>
  <img src = "/image/survived.png" style="width:400px;"><br><br>
- <b>PClass:</b>This feature renders the passenger division. The tourists could opt from three distinct sections, namely class-1, class-2, class-3. The third class had the highest number of commuters, followed by class-2 and class-1. <br><br>
  <img src = "/image/pclass.png" style="width:400px;"><br><br>
- <b>Name:</b> It represents the name of the passenger.<br><br>
- <b>Sex: </b>It represents the gender of the particular passanger. Approximately 65% of the tourists were male while the remaining 35% were female.<br><br>
  <img src = "/image/sex.png" style="width:400px;"><br><br>
- <b>Age:</b> It represents the age of the passanger. The youngest traveler onboard was aged around two months and the oldest traveler was 80 years. The average age of tourists onboard was just under 30 years.<br><br>
- <b>SibSp:</b>SibSp is the number of siblings or spouse of a person onboard. A maximum of 8 siblings and spouses traveled along with one of the traveler.<br><br>
  <img src = "/image/sibsp.png" style="width:400px;"><br><br>
- <b>Parch:</b> Similar to the SibSp, this feature contained the number of parents or children each passenger was touring with. A maximum of 9 parents/children traveled along with one of the traveler.<br><br>
- <b>Ticket:</b> Ticket number, datatype object. We notice below that a ticket number might belong to more than one passenger and some of the tickets has a string prefix.<br><br>
- <b>Fare: </b> By splitting the fare amount into four categories, it was obvious that there was a strong association between the charge and the survival. The higher a tourist paid, the higher would be his chances to survive.<br><br>
  <img src = "/image/fare.png" style="width:400px;"><br><br>
- <b>Cabin: </b> More than 70% values are null in this column. This represents the cabin of the passanger which was alloted to the passenger.<br><br>
- <b>Embarked:</b> Embarked implies where the traveler mounted from. There are three possible values for Embark — Southampton(S), Cherbourg(C), and Queenstown(Q).<br><br>
  <img src = "/image/embarked.png" style="width:400px;"><br><br>
<h3>Our model predicts 82% of the time, a passengers survival correctly</h3><br><br>

## Get in Touch 😊
<a href="https://www.linkedin.com/in/biprajit-suklabaidya-9950b1208/"><img src ="/linkedin.png" style="width:40px;"></a>
<a href="https://github.com/Biprock"><img src ="/github.png" style="width:40px;"></a>
