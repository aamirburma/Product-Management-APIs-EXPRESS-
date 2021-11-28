# Product-Management-APIs-EXPRESS-
<h1 style="text-align:center" align="center">SCHEMA</h1>
<ol>
    <li><h4>PRODUCT</h4></li>
    <ul>
        <li>product id : String</li>
        <li>title : String</li>
        <li>price : String</li>
        <li>category : Array of String</li>
        <li>company id : String</li>
        <li>seller id : Array of String</li>
    </ul>
    <li><h4>COMPANY </h4></li>
    <ul>
        <li>company id : String</li>
        <li>name : String</li>
        <li>product ids : Array of String</li>
    </ul>
    <li><h4>SELLER</h4></li>
    <ul>
        <li>seller id : String</li>
        <li>name : String</li>
        <li>product ids : Array of String</li>
    </ul>
</ol>
<hr />
<h1 style="text-align:center" align="center">Operations</h1>
<ol>
    <li>ADD</li>
    <ul>
        <li>add new company</li>
        <li>add new seller</li>
        <li>add new product</li>
    </ul>    
    <li> RETRIEVE </li>
    <ul>
        <li>fetch company details based on product name</li>
        <li>fetch seller details based on product name</li>
        <li>fetch all products of a company</li>
        <li>fetch all products of a seller</li>
    </ul>
    <li> UPDATE </li>
    <ul>
        <li>update company (add/remove products)</li>
        <li>update seller (add/remove products)</li>
        <li>update product (add/remove category)</li>
    </ul>
    <li> DELETE </li>
    <ul>
        <li>delete company</li>
        <li>delete seller</li>
        <li>delete product</li>
    </ul>
</ol>