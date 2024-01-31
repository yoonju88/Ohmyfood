Oh my food

la visibilité les icônes sur le Code-pen: 

inclure le CDN : 
Appliquer ce link dans <head> de sur le docuement html. 
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css"
        integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w=="
        crossorigin="anonymous" referrerpolicy="no-referrer"/>


Simplifiez le CSS avec Sass. 
https://sass-lang.com/documentation/modules/color/

utilise "variable" pour les codes répétives 

ex) les couleurs

$main-color: #a5b4fc; 

.nav{
background-color: $main-color; 
}

utilise "mixins"
ex) 

@mixin title-shadow {
        text-shadow: .50em .50em black;
}

.intro-title {
        @include title-shadow;
}

utilise "darken($color,$amount)"

@mixin title-shadow {
        text-shadow: .50em .50em darken($main-color,90%);

.intro-title {
        @include title-shadow;
}
}

















