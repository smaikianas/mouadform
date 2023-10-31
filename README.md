# mouadform
<!DOCTYPE html>
<html>

  <head>
      <meta charset="UTF-8">
      <link rel="stylesheet" href="form.css">
      
      <title>Formulaire</title>
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=Calistoga&family=Cuprum&family=Germania+One&family=Khand:wght@500&family=Lilita+One&family=Londrina+Solid:wght@300&family=Patua+One&display=swap" rel="stylesheet">
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=AR+One+Sans:wght@500&family=Basic&family=Calistoga&family=Cuprum&family=Fira+Sans+Extra+Condensed:ital,wght@0,400;1,200;1,300&family=Germania+One&family=Khand:wght@400;500&family=Lilita+One&family=Londrina+Solid:wght@300&family=Patua+One&family=Roboto+Condensed:wght@300&display=swap" rel="stylesheet">
  </head>
  
  <body>
    <div >
          <h1>Formulaire:</h1> 
            <form method="get" action="nouveauCV.html" id="Form" >

              <label for="nom">Nom:</label>
                <input class="po" type="text" id="nom" required placeholder="Votre Nom" name="nom">
              
              <label for="prenom">Prénom:</label>
                <input class="po" type="text"  placeholder="Votre Prenom" name="prenom" >

              <label for="age">Age:</label>
                <input class="po" type="number"  required placeholder="Votre Age" name="age" min="18">

              <label for="TEL"><i class="fa fa-volume-control-phone" aria-hidden="true"></i>Tel:</label>
                <input class="po" type="tel" placeholder="Saisir Votre Numero De Telephone" name="tel">

              <label for="email">Email:</label> 
                <input class="po" type="email" id="email" name="email" value="" placeholder="Votre Email" />
              
                                                       
                <label for="adresse"><i class="fa fa-envelope-open" aria-hidden="true"></i>Adresse:</label>
                  <input class="po" type="address" id="adresse" name="adresse" value="" placeholder="Votre Address" >

              <label for="titre">Titre de CV:</label> 
                <input class="po" type="text" id="titre" name="titre" value="" placeholder="Votre Titre de CV" />

                <br><br>
              

                <label for="objectif"><i class="fa fa-graduation-cap" aria-hidden="true"></i>Objectif Professional:</label><br>
                  <textarea placeholder="objectif professional" name="objprf"></textarea><br><br>

                  <label for="diplome"><i class="fa fa-graduation-cap" aria-hidden="true"></i>Formation Et Diplomes:</label><br>
                  <textarea placeholder="saisir votre diplme" name="dip"></textarea><br><br>

                  <label for="diplome"><i class="fa fa-graduation-cap" aria-hidden="true"></i>Compétences Techniques:</label><br>
                  <textarea placeholder="saisir votre competences technique" name="tec"></textarea><br><br>

                  <label for="diplome"><i class="fa fa-graduation-cap" aria-hidden="true"></i>Compétences linguistiques:</label><br>
                  <textarea placeholder="saisir votre competences linguistiques" name="lin"></textarea><br><br>

          
                <input  class="f" type="submit" value="Valider"><br>

            </form>
        </div>
        <script type="text/javascript" src="formulaire.js"></script>
  </body>
</html>
* {
    max-width: 1500px;
    margin: 0;
    padding: 0;
    text-align: center;
 }


html{

    background:linear-gradient(rgba(0, 0, 0, 0.438),rgba(0, 0, 0, 0.527)), url(ana.jpg) no-repeat;
    background-size: cover;
 }

 body {

    color: #443030;
    font-family: Arial, san-serif;
    min-width: 500px;
    min-height: 100vh;
 }
 
form{
    display: flex;
    flex-direction: column;
}
label{
    color: rgb(255, 255, 255);
    padding: 5px;
    font-size: 20px;
}
div{
    background-color: rgba(3, 82, 82, 0.411);
    margin: 0;
}
input.po{
    margin: 0 480px 20px 480px;
    border-radius: 8px;
    height: 35px;
    color: rgb(0, 0, 0);
}
input.pi{
    margin: 5px 17px;
    color: rgb(0, 0, 0);
}
section{
    display: flex;
    justify-content: center;
    color: aliceblue;
}
h1 {
    text-align: center;
    color: aliceblue;
    padding: 40px 0 40px 0;
    text-decoration: underline;
 }
 h4{
    margin: 0 0 20px 0;
 }
textarea{
    margin: 0 480px 8px 480px;
    color: #000;
    border: 1px solid black;
    border-radius: 5px;
    min-height: 40px;
    padding: 3px;
}

input.f{
    margin: 10px 580px;
    border: #000 solid 1px;
    border-radius: 8px;
    height: 40px;
    font-size: 15px;
    font-weight: 900;
}
input{
    color: #000;
    border: #000 solid 1px;
    border-radius: 8px;

}

label{font-weight: 800;}
