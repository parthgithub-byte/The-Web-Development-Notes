There are three main types of lists:
- **Unordered List**
- **Ordered List**
- **Description List**

1] ***Unordered List***
Here, the list of contents is mentioned in the `<ul>` tag. By default, the disc bulleted contents are displayed and each content is given in the new line using the list tag (`<li>`).
Eg:
    `<ul>`  
        `<li>`HTML`</li>`  
        `<li>`CSS`</li>`  
        `<li>`Javascript`</li>`  
        `<li>`Mediawiki(PHP)`</li>`  
        `<li>`MySQL`</li>`  
        `<li>`JSON APIs`</li>`  
        `<li>`Python Scripts`</li>`  
        `<li>`CDN`</li>`  
    `</ul>`  
    is displayed as:
        HTML
        CSS
        Javascript
        Mediawiki(PHP)
        MySQL
        JSON APIs
        Python Scripts
        CDN

Now, these bullets can be customized specifically to some certain types like: circle, square, disc and none.
Eg:
    `<ul>`
        `<li>` Zero (Default)`</li>`  
        `<li` `type`="circle">One (Circle)`</li>`  
        `<li` `type`="square">Two (Square)`</li>`  
        `<li` `type`="none">Three (None)`</li>`  
        `<li` `type`="disc">Four (Disc)`</li>`  
    `</ul>`  
    is displayed as:
    <ul>
        <li> Zero (Default)</li>
        <li type="circle">One (Circle)</li>
        <li type="square">Two (Square)</li>
        <li type="none">Three (None)</li>
        <li type="disc">Four (Disc)</li>
    </ul>

---

2] ***Ordered List***
An ordered list sequentially gives the listed contents. Similar to the unordered list, ordered list elements are given with the list tag(`<li>`). All the `<li>` tags come under the `<ol>` tag.
Eg:
 `<p>`Steps to make tea:`</p>`  
    `<ol>`  
       `<li>`Place a vessel on stove, put half cup water in it.`</li>`  
       `<li>`Put two spoons tea powder.`</li>`  
       `<li>`After the water boils enough, put four spoons of sugar.`</li>`  
       `<li>`Then pour one mug milk in it.`</li>`  
       `<li>`Let it boil enough at high flame`</li>`  
       `<li>`Serve in two small cups`</li>`  
   `</ol>`  
    displays as:
    Steps to make tea:

    1. Place a vessel on stove, put half cup water in it.  
    2. Put two spoons tea powder.  
    3. After the water boils enough, put four spoons of sugar.  
    4. Then pour one mug milk in it.  
    5. Let it boil enough at high flame  
    6. Serve in two small cups  

There are also types of ways to present the order of a list with their markers (initials in each set):
(1) Natural numbers 1,2,3,...               **type="1"**
(2) Small roman numbers i,ii,iii,iv,....   **type="i"**
(3) Capital roman numbers I,II,III,IV,.... **type="I"**
(4) Small alphabets a,b,c,d,....           **type="a"**
(5) Capital alhabets A,B,C,D,....          **type="A"**

Eg:
    `<ol>`  
        `<li>`Ek`</li>`  
        `<li` `type`="a">Don`</li>`  
        `<li` `type`="a">Tin`</li>`  
        `<li` `type`="i">Chaar`</li>`  
        `<li` `type`="I">Paach`</li>`  
        `<li` `type`="I">Saha`</li>`  
        `<li` `type`="A">Saat`</li>`  
        `<li` `type`="1">Aath`</li>`  
    `</ol>`  
    displays as:
    <ol>
        <li>Ek</li>
        <li type="a">Don</li>
        <li type="a">Tin</li>
        <li type="i">Chaar</li>
        <li type="I">Paach</li>
        <li type="I">Saha</li>
        <li type="A">Saat</li>
        <li type="1">Aath</li>
    </ol>
Obviously, the natural numbers are the by default used ordered list bullets.

---

3] ***Description List***
A descrption list contains description terms an their respective descriptive definitions. So, it's like an unordered list of unordered lists.
Here there are two types of tags for listings:

I] Description Term Tag (`<dt>`)
II] Description Definition Tag (`<dd>`)

Both the tags come under the description list tag (`<dl>`).
There can be multiple description `<dt>` mentioning multiple description terms and each term has its own list defining it given under the respective `<dl>` following them.
Eg:
    Single Description List
    `<dl>`  
        `<dt>`Features of My Laptop`</dt>`  
        `<dd>`OS: Windows 10`</dd>`  
        `<dd>`Processor: i5 5th Generation`</dd>`  
        `<dd>`Storage: 440 Gb`</dd>`  
    `</dl>`  
    
    displays:
    <p>Single Description List</p>
    <dl>
        <dt>Features of My Laptop</dt>
        <dd>OS: Windows 10</dd>
        <dd>Processor: i5 5th Generation</dd>
        <dd>Storage: 440 Gb</dd>
    </dl>
    
    or

Multiple Description Lists
    `<dl>`  
        `<dt>`Shonen Anime: `</dt>`  
        `<dd>`Naruto`</dd>`  
        `<dd>`One Piece`</dd>`  
        `<dd>`Bakuman`</dd>`  
        `<dt>`Sports`</dt>`  
        `<dd>`Hajime no Ippo`</dd>`  
        `<dd>`Haikyuu`</dd>`  
        `<dd>`Baby Steps`</dd>`  
        `<dt>`Shoujo`</dt>`  
        `<dd>`Kimi ni Todoke`</dd>`  
        `<dd>`Kaichou wa Maid-sama`</dd>`  
        `<dd>`Fruit Basket`</dd>`  
    `</dl>`  

    displays:
    Multiple Description Lists
  <dl>
        <dt>Shonen Anime: </dt>
        <dd>Naruto</dd>
        <dd>One Piece</dd>
        <dd>Bakuman</dd>        
        <dt>Sports</dt>
        <dd>Hajime no Ippo</dd>
        <dd>Haikyuu</dd>
        <dd>Baby Steps</dd>
        <dt>Shoujo</dt>
        <dd>Kimi ni Todoke</dd>
        <dd>Kaichou wa Maid-sama</dd>
        <dd>Fruit Basket</dd>
    </dl>
