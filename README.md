# FreeFire_League_Prediction
__NOTE__ : __The dataset used was created using Freefire Season 21 ( ranked mode ) as reference__

FreeFire is a well known Battle Royale game . It has league order according to which it rank players
following from least rank : 
* Brown
* Silver
* Gold
* Platinum
* Diamond
* Heroic
* Grandmaster

So I have divided these rank order in 2 classes 
* Below Heoroic as 0
* Heroic and above as 1

Here's the structure of table with one instance 

WIN_RATE | TOP 3 RATE | K/D | MOST KILLS | HEADSHOT RATE |  HEROIC LABEL
-------- | ---------- | --- | --------- | ------------- | -------------
62.15 |	81.28 |	9.56 | 18 |	18.37 |	1

__WIN_RATE__  - Rate of matches won by player

__TOP 3 RATE__ - Rate of player securing atleast 3rd rank in Battle Royale (BR)

__K/D__ - Kill to Death Ratio

__MOST KILLS__ - Maximum no of kills made by the player in BR

__HEADSHOT RATE__ - Rate of player made headshot 

__HEROIC LABEL__ - As described above it has two values (0/1) (I have used HEROCIC as label as it act as intermediator between 2 classes )

* TRAINING COLUMNS - The first 5 columns
* TEST COLUMN - HEROIC LABEL

I have used __Logistic Regression__ Algorithm for this Binary Classification.
