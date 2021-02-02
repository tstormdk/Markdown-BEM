# Markdown-BEM
03.50 - objekt orienteret kodning. "Decoupling" - handler om at sortere de forskellige CSS elemeter, så de bliver skilt ad og det giver mere mening. Træk de rigtige objekter ud og opdel dem i de mest relevante objekter. 

05.20 - finde et objekt der står alene, som ikke har strenge til en masse andre objekter. Den gør kun én ting og gør den ting rigtig godt. 

06.30 - han fortæller om Nicole Sullivan's opdagelse af, hvordan man kan samle objekter, der har en rød tråd, til én "class" men i stedet for, kan genbruge igen og igen. Identifisere et element 1 gang også bruge det igen og igen. 

08.57 - handler om SMACSS (Scalable modular architecture for css). Hvor der bliver snakket om Base, Layout, Module, State og Theme, hvilket er en måde, man kan dele sin CSS semantisk korrekt op.

19.05 - snakker om, at jo mere specifik din defination er jo mere vigtig er den. Derfor er det ikke smart at lave simple css-styles, hvor man kun fanger et element som f.eks H1 eller body.

20.50 - viser eksempel på, hvordan man ikke skal stille sit CSS op:

.body h1 --> mere specifik{
    color: red;
}
.alternate ->> single selector{
    color: green;
}
´´<div class ="body">
  <h1 class="alternate">Awesome</h1>
</div>´´


22.06 - handler om at ">" gør det mere specifikt og # må man aldrig bruge til styling. Man kan ikke overskygge et ID, derfor kan man ikke gå tilbage senere og ændre på det. 

24.20 - handler om, at når du laver en syntakt i CSS, hvor du skal ind og fange specifikke elementer som f.eks

 .body ul li{
    color: red;
} 
Så skal der læses alle de forskellige elementer. Derfor er det bedre og nemmere at lave specifikke klasser, der fanger lige præcis det element der skal bruges, så kan det også genbruges.

Hvad fik jeg ud af videoen? 
Jeg har lært, at det er bedre at lave specifikke klasser til de forskellige styles, så man kan genbruge stylen senere. 
Derudover, skal syntaktsen være let at forstå og indholde elementets navn, parent-elementet og child-elementets navn. På den måde er det nemt at forstå og nemt at videregive et projekt til en anden. 
