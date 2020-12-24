# Learn_JSON

<!-- JSON -->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JSON</title>
</head>

<body>

    <script>

        // Javascript object notation 
        // JSON is a piece of informations in string format. Most of the API provides data in JSON format, we need to 
        // convert the JSON to a object and the should convert back to JSON to handle those kind of datas
        // template literals (``) to include jason in a .js file. you can directly insert jSON in .json file without template literals
        //eg:

        const strObj = `{
          "name" : "Vishnu",
          "age"  : 25,
          "id"   : 1
      }`
        console.log(strObj); // this will print strJSON as string
        //to check that
        console.log(typeof strObj);

        //convert JSON to an object
        //************************//
        //JSON.parse() will help to convert a JSON in to an object
        //eg:

        let strJSON = JSON.parse(strObj);
        console.log(strJSON);
        console.log(typeof strJSON);

        //convert an object to an JSON
        //************************//
        //JSON.stringify() will help to convert a JSON in to an object
        //eg:

        let objJSON = JSON.stringify(strJSON);
        console.log(objJSON);
        console.log(typeof objJSON);
    </script>
</body>

</html>
