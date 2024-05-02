# Atelier Docker

### Realisé par

- **SAAD LAKNIN**
- **AMINE MOUNJIDE**
- **AZEDINE LAOUISSI**
- **YOUSSEF SOUAIDI**

### Encadré par

- **Pr  F. Benabbou**

# Installation Docker

```php
<?php
$servername = "db";
$dbname = "marssa_maroc";
$username = "test";
$password = "pass";
try {
    $con = new PDO("mysql:host=$servername;dbname=$dbname", $username, $password);
    $con->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
   
} catch (PDOException $e) {
    header('HTTP/1.1 500 Internal Server Error');
    echo "Erreur de connexion à la base de données : " . $e->getMessage();
}
```

