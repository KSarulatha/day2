# day2
1.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Program to search for a particular character in a string</h1>
</body>
<script>
    let str='Hello myself Sathish Kumar'
    console.log(str);
    console.log('searching for S')
    console.log('Found S at '+str.search('S'))
</script>
</html>


2.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Program to convert minutes to seconds</h1>
</body>
<script>
    function timeConverter(num){
        var min=num*60;
        return min+' Sec'
    }
    console.log('converted 2 min to second '+timeConverter(2));
    console.log('converted 10 min to second '+timeConverter(10));
    console.log('converted 15 min to second '+timeConverter(15));

</script>
</html>

3.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Program to search for a element in a array of strings</h1>
</body>
<script>
function findArr(str)
{
var array=["Hello",,"How","Are","You"];
console.log(array)
    for(let i=0;i<array.length;i++)
        {
            if(array[i]==str)
            {
                console.log('Found');
            }
            else
            {
            console.log('Not found');
            }
            return str;
        }
        
}
console.log('Searching for '+findArr('Hello'));

</script>
</html>

4.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Program to display only elements containing 'a' in them from a array</h1>
    <p id="a"></p>
</body>
<script>
let arr=['hello','thief','fruit','apple','mango'];
var element;
for(let i=0;i<arr.length;i++)
{
element=arr[i].search('a');
if(element>=0){
    console.log(arr[i]);
}
}


</script>
</html>

5.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Print an array in reverse order</h1>
</body>
<script>
let arr=['mom','Dad','sis','Bro','Friend','family']
console.log('correct order is '+arr);
console.log(arr.reverse());
console.log('reverse order is '+arr);

</script>
</html>
