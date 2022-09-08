# assignment2-Alapati

 # Deepika Alapati

#### Museum of Fine Arts
The Museum of Fine Arts, often recognized as the Boston Museum of Fine Arts, is a Boston national artifact and one of the largest art museums in the world thanks to its **well-balanced collection**. The Boston Athenaeum library's art holdings served as the foundation of the museum's initial collection when it opened its doors in **1870**.<b>

### Airport Directions
The airport that is closest to the museum is Boston Logan international airport.

#### Directions
1.Get on MA-1A S from Airport Rd - Arrival Level

2.Continue on MA-1A S. Take Storrow Dr to Charlesgate. Take the exit toward Fenway from

3.Continue on Charlesgate. Take Fenway and Hemenway St to Huntington Ave

#### Places around museum
* Fenway Park.
* Freedom Trail.
* Museum of Fine Arts.
* Boston Tea Party Ships & Museum.
* North End.

-------------------------------------------------------------------
### Tables
The table introduces the cities recommend to visit,like these beautiful cities Paris,Seoul,New Orleans,Sydney.In the first row it has the name of the city,locations to visit in the city and amount of time .

|Name of the city|Locations in the city             |Time to spend|
|----------------|----------------------------------|-------------|
|Paris           |Eiffel Tower,Louvre Museum        |7hours       |
|Seoul           |Gyeongbokgung Palace,N Seoul Tower|9hours       |
|New orleans     |French Quarter,Frenchmen Street   |8hours       |
|Sydney          |Sydney Opera House,Bondi Beach    |9hours       |


-------------------------------------------------------------------

### Pithy Quotes

> "Live for each second without hesitation."— *Elton John*

> "Love Yourself" - *BTS*

-------------------------------------------------------------------

### Code Fencing
Sorting Numbers

>[article](https://css-tricks.com/introducing-sass-modules/)

$@function quick-sort($list) {
  $less:  ();
  $equal: ();
  $large: ();

  @if length($list) > 1 {
    $seed: nth($list, ceil(length($list) / 2));

    @each $item in $list {
      @if ($item == $seed) {
        $equal: append($equal, $item);
      } @else if ($item < $seed) {
        $less: append($less, $item);
      } @else if ($item > $SEED) {
        $large: append($large, $item);
      }
    }

    @return join(join(quick-sort($less, $order), $equal), quick-sort($large, $order));
  }

  @return $list;
}



> [sass snippet source](https://css-tricks.com/snippets/sass/sorting-function/)




[AboutMe.md](C:\Users\s550002\Desktop\webapps-repos\assignment2-Alapati\AboutMe.md)