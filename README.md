/* Color Theme Swatches in Hex */
/*
.principal { color: #F2133C; }
.background { color: #0A3B59; }
.Fashion-3-hex {color: #0f698c; }
.Fashion-4- { color: #0d758C; }
.destaque { color: #F2B9AC; }
*/

.page-wrapper {
    position: relative;
}

.xplanation {
    width: 60%;
    border-right: #1f295c solid 1px;
    padding-right: 2%;
}
#design-selection {
    position: absolute;
    top: 480px;
    left: 62%;
    padding-left: 1%;
    padding-right: 1%;
}


.main footer {
    margin: 4%;
}

.main footer a {
    border: solid 2px #1f295c;
    padding: 0.5em;
}

aside ul {
    list-style-type: nome;
}

aside ul li {
    margin: 1em;
    text-align: center;
}

.page-wrapper {
    width: 80%;
    max-width: 1280px;
    margin: auto;
}

#zen-intro {
    height: 550px;
}

#design-acrhives {
    display: none;
}

#zen-intro header {
    background-color: #1f295c;
    color: #fbfcfd;
}

#zen-intro header h1, #zen-intro header h2 {
    display: inline-block;
}
#zen-intro header h1 {
    margin-left: 1em;
    margin-right: 1em;
}

html {
    background: #0A3859;
    color: #f2133c;

    font-size: 18px;
    font-family: Helvetica, sans-serif;
}

p {
    text-indent: 1em;
}


h1, h2, h3 {
    text-align: center;
}

h1 {font-size: 1.8rem;}
h2 {font-size: 1.4rem;}
h3 {font-size: 1.2rem;}

.summary {text-align: right;}
.main p {line-height: 1.5;}

abbr {font-variant: small-caps;}

.supporting footer {
    display: flex;
    justify-content: space-evenly;
}

.benefits {
    display: flex;
    border-top: #1f295c solid 1px;
    border-bottom: #1f295c solid 1;
}

.benefits p {
    flex-basis: 70%;
}

.benefits h3 {
    order: 2;
    align-self: center;
    flex-basis: 30%;
}

.participation {
    display: flex;
    flex-wrap: wrap;
    border-top: #1f295c solid 1px;
}
.participation h3, participation p{
    flex-basis: 50%;
}

a {
    color: #ff1492;
}

a:hover {
    color: ff149187;
}

.main p:first-of-type:first-letter {
    font-size: 3em;
    font-family: "Times New Roman", Times, serif;
    float: #1f295c;   
}

.design-selection li {
    border-top: #1f295c solid 1px;
    padding-top: 5px;
}

.design-selection li:last-of-type {
    border-bottom: #1f295c solid 1px;
    padding-bottom: 5px;
}

*/
@media screen and (max-width: 768px) {
   .design-selection {
    position: static;
    width: 100%;
   } 
   
   .explanation {
    border-right: nome;
    width: 100%;
   }

   #zen-intro {
    height: auto;
   }

   .participation {
    flex-direction: column;
   }

   p {
    text-indent: 0;
   }
}

/*
*/
@media print{
    html {
        font-family: 'Times New Roman', Times, serif;
    }

    #zen-intro header {
        background-color:#fbfcfd;
        color:#1f295c;
    }

    .design-selection {
        position: static;
        width: 100%;
       } 
       
       .explanation {
        border-right: nome;
        width: 100%;
       }
}
