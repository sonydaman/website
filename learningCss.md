css is cascading style sheet
css 3 type 
    inline css -- that is dangerous code
    internal css -- that is fine
    external css -- best way
 style --   
    key:value;
    key1:value1;
    key1:value1;
<h1 style='background-color:tomato;color:white'>Heading<h1>

<head>
    <style>
        .heading-1{
            background-color:tomato;
            color:white
        }
        #heading-1{
            background-color:tomato;
            color:white
        }
    </style>
</head>

how to define a class,id--
    <h1 class="heading-1">Heading1<h1>
    <h1 id="heading-1">Heading1<h1>
class should be denote from .
id should be denote from #
we can add multiple class in a document
we can use unique id in a document

<head>
    <link>
</head>
what is box model
    ---margin, top,right,bottom,left
        12px 12px 12px 12px;
        12px;
        12px 10px; (top,bottom - 12px , right ,left 10px)
    ---border, top,right,bottom,left
        border : 1px solid #000;
    ---padding, top,right,bottom,left
        12px 12px 12px 12px;
        12px;
        12px 10px; (top,bottom - 12px , right ,left 10px)
    ---content


    margin-top:10px
    margin-bottom:10px
    margin-right:0px
    margin-left:0px

css3,5
float : left,
display : inline-block;
display : flex , grid
            flex - 1 Dimension
            grid - 2 Dimension

    flex-direction : row ,column
    flex-basis:(1% - 100%)
    gap:3
    flex-wrap:wrap;
    justify-content:center,space-between,space-around,flex-start,flex-end
    <div flex>
        
        <div>
        </div>

        <div>
        </div>

    </div>


    <table>
        <tr>
            <td>1</td>
        </tr>
    </table>

grid
    row,column

    grid-template-columns: 33% 33% 33%
    grid-template-columns: 1fr 1fr 1fr
    grid-template-columns: 16px 1fr 8px

    grid-template-areas:
        "header header header"
        "side   main   ....."
        "footer footer footer"
    .header{
        grid-area:header;
    }

    position
        static default
        fixed
        absolute
        relative
        sticky

        unset
        initial


    top:0
    left:0
    bootom:0



    ::after
        content : '';
    ::before

