# goit-markup-hw-02

1.  Как правильно задать например элементу, который лежит внутри ссылки изменения псевдокласса
    hover, focus. Например у нас есть список 
    ``` html
    <ul> 
    <li class="item"> 
    <a class="link">
    <svg class="icon">
    </svg>
    </a>
    </li>
    </ul>
    ```

    И мы хотим,что бы при наведение на ссылку менялось состояние ховера у элемента внутри ссылки,а именно что бы цвет елемента с классом **.link** менялся на
    синий.

``` css .link:hover .icon { color: blue; } ```
И так получается что иконка при ховере сылки будет менять свой
цвет на синий и я не могу задать hover чисто для иконки, так как тогда будет - при ховере самой иконки, она будет менять
цвет.
