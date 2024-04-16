1ый вид селектора: Tag name   (всегда идет приоритет с css)
будем обращяться по названию тега 
body{ 
     background: #ddd;
    }
2ой вид по классу; суть в том что вибраешь что то именное   div class="card  писать через точку
.class{
    padding: 10px;
    margin-bottom: 10px;
    background: #fff;
}
3ий по ID: header id="header" нужно в начале писать #
#header{
    background: darkgoldenrod;
    padding: 10px;
4ый ТЕГ КОГДА ОБРАЩЯЕМСЯ ОТ РОДИТЕЛЬСКОГО ТЕГА К ДОЧЕРНЕМУ ТО ЕСТЬ от DIV к P род тег(class="card") 
<div class="card html">
        <h2>HTML</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugiat, dignissimos.</p>
5ый множественный селектор (относиться ко всем) писать в одном теге
#header, .card{
    margin-bottom: 10px;
}
6ый ЗВЕЗДОЧКА ,оброщается ко всем элементам 
* {
    
}