<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>layout</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <h1>BOX MODEL</h1>
    </header>
    <div class="container">
      <section>
        <h2>Margin</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias
          consequatur incidunt quis pariatur, reprehenderit repudiandae
          recusandae autem suscipit necessitatibus error tenetur vero nulla
          nostrum culpa ducimus repellat eligendi! Quia, ratione reiciendis.
          Labore culpa corrupti sint ipsum illo repudiandae corporis distinctio
          inventore facilis molestiae. Provident mollitia tempora pariatur
          perspiciatis deserunt dicta aut adipisci impedit, saepe recusandae
          doloribus reiciendis debitis voluptatem fuga totam corporis ipsum
          exercitationem incidunt repellat placeat.
        </p>
      </section>
      <section>
        <h2>Border</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias
          consequatur incidunt quis pariatur, reprehenderit repudiandae
          recusandae autem suscipit necessitatibus error tenetur vero nulla
          nostrum culpa ducimus repellat eligendi! Quia, ratione reiciendis.
          Labore culpa corrupti sint ipsum illo repudiandae corporis distinctio
          inventore facilis molestiae. Provident mollitia tempora pariatur
          perspiciatis deserunt dicta aut adipisci impedit, saepe recusandae
          doloribus reiciendis debitis voluptatem fuga totam corporis ipsum
          exercitationem incidunt repellat placeat. 
        </p>
      </section>
      <section>
        <h2>Padding</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias
          consequatur incidunt quis pariatur, reprehenderit repudiandae
          recusandae autem suscipit necessitatibus error tenetur vero nulla
          nostrum culpa ducimus repellat eligendi! Quia, ratione reiciendis.
          Labore culpa corrupti sint ipsum illo repudiandae corporis distinctio
          inventore facilis molestiae. Provident mollitia tempora pariatur
          perspiciatis deserunt dicta aut adipisci impedit, saepe recusandae
          doloribus reiciendis debitis voluptatem fuga totam corporis ipsum
          exercitationem incidunt repellat placeat.
        </p>
      </section>
      <section>
        <h2>Content</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias
          consequatur incidunt quis pariatur, reprehenderit repudiandae
          recusandae autem suscipit necessitatibus error tenetur vero nulla
          nostrum culpa ducimus repellat eligendi! Quia, ratione reiciendis.
          Labore culpa corrupti sint ipsum illo repudiandae corporis distinctio
          inventore facilis molestiae. Provident mollitia tempora pariatur
          perspiciatis deserunt dicta aut adipisci impedit, saepe recusandae
          doloribus reiciendis debitis voluptatem fuga totam corporis ipsum
          exercitationem incidunt repellat placeat.
        </p>
      </section>
    </div>
    <footer>
      <div>
        <h1>THE END</h1>
      </div>
    </footer>
  </body>
</html>
@import url("https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Fjalla+One&family=Playwrite+AU+QLD:wght@100..400&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  background-color: #e2fdff;
}
section p {
  padding: 30px 30px;
  color: rgb(109, 109, 109);
  text-align: justify;
  font-size: large;
  word-spacing: 3px;
  line-height: 23px;
  font-family: "Playwrite AU QLD", cursive;
}
section h2 {
  padding: 20px 30px;
  font-family: "Fjalla One", sans-serif;
  text-align: center;
  letter-spacing: 3px;
  text-decoration: underline;
}
section {
  /* border: 3px solid #3d5a80  ;  */
  width: 500px;

  border-radius: 10px;
  background-color: #ffe45e;
  margin: 40px;
}
h1 {
  background-color: #3d5a80;
  color: #e0fdff;
  font-family: "Bebas Neue", sans-serif;
  word-spacing: 18px;
  letter-spacing: 15px;

  text-align: center;
  padding: 20px 50px;
}
/* div {
  background-color : #3d5a80 ;
} */
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
