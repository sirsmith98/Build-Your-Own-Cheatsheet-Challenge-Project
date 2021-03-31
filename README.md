# Build-Your-Own-Cheatsheet-Challenge-Project
<!DOCTYPE html>
<html lan="eng">
<head>
    <title>Cheatsheet: CSS Properties</title>
    <link href="styles.css" type="text/css" rel="stylesheet">
</head>
<body>
  <header>
    <h1>CSS Properties</h1>
  </header>
  <main>
    <table>
      <thead>
      <tr>
        <th scope= "col">Properties</th>
        <th scope= "col">Syntax</th>
        <th scope= "col">Description</th>
        <th scope= "col">Values</th>
      </tr>
      </thead>
      <tbody>
      <tr>
        <td>Font Family</td>
        <td class= "syntax">font-family:</td>
        <td>The property used to change the typeface of text.</td>
        <td class= "syntax">
          <ul>
            <li>Garamond;</li>
            <li>Georgia;</li>
            <li>sans;</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Font Size</td>
        <td class= "syntax">font-size:</td>
        <td>The property used to change the size of text on the web page.</td>
        <td class= "syntax">
          <ul>
            <li>18px;</li>
            <li>25px;</li>
            <li>40px;</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Font Weight</td>
        <td class= "syntax">font-weight:</td>
        <td>This property controls how bold or thin text appears.</td>
        <td class= "syntax">
          <ul>
            <li>bold;</li>
            <li>normal;</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Text Align</td>
        <td class= "syntax">text-align:</td>
        <td>This property is used to align text on the web page.</td>
        <td class= "syntax">
          <ul>
            <li>left;</li>
            <li>center;</li>
            <li>right;</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Color</td>
        <td class= "syntax">color;</td>
        <td>This property changes the foreground color of an element.</td>
        <td class= "syntax">
          <ul>
            <li>red;</li>
            <li>aqua;</li>
            <li>grey;</li>
          </ul>
        </td>
      </tr>
      </tbody>

    </table>
  </main>
</body>
</html>


body {
  background-color: lavender;
  font-family: Garamond;
  text-align: center;
}

h1 {
  color: navy;
}

table {
  background-color: aliceblue;
  border: 2px solid darkslateblue;
  margin: 4em;
}

thead {
  background-color: lightskyblue;
}

th {
  color: navy;
  padding: 4px;
}

td {
  padding:1px;
  border-top: 1px solid darkslateblue;
  text-align: left;
}

.syntax {
  font-family: monospace;
  color: royalblue;
}

