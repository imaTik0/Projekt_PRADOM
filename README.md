# Własne repozytorium kodu
 
This project simply solves `this` problem.
 
Simple code example 
 
```<?php
$servername = "localhost";
$username = "username";
$password = "password";
$dbname = "myDB";

// Create connection
$conn = new mysqli($servername, $username, $password, $dbname);
// Check connection
if ($conn->connect_error) {
  die("Connection failed: " . $conn->connect_error);
}

$sql = "SELECT id, firstname, lastname FROM MyGuests";
$result = $conn->query($sql);

if ($result->num_rows > 0) {
  // output data of each row
  while($row = $result->fetch_assoc()) {
    echo "id: " . $row["id"]. " - Name: " . $row["firstname"]. " " . $row["lastname"]. "<br>";
  }
} else {
  echo "0 results";
}
$conn->close();
?>
```
 
## Dokumentacja
 
Moja dokumentacja dotycząca pracy w domu na zajęcia "Tworzenie stron i aplikacji internetowych".
 
## Instalacja
 
Instalacja została wykonana na zajęciach.
 
```
https://github.com/imaTik0/pa01ti4
```
 
## Cel i funkcje
 
* Zbiór elementów pracy w domu
* Możliwość pomocy kolegów z zespołu projektowego
* Nadzór kierownika projektu
 
## Skład projektowy
 
* Głowny nadzór: https://github.com/Michal3456
* Lider zespołu: https://github.com/imaTik0
* Tester: https://github.com/radeks2001
* DevOps: https://github.com/reddvaske
 
## Licencja
 
Ten projekt jest udostępniany na licenji MIT. Szczególowe informacje można znaleźć w dołączonym pliku LICENCJA.
 
## Autor
 
Paweł Aniszewski
