# Chat Project

The project is a Chat Web App, groups will be set randomly, you will use https://www.firebase.com/ (a Remote Database) and some CSS Preprocessors http://lesscss.org/ & http://sass-lang.com/ !

First day, you will focus on the UX / UI Design of the app, and write some specifications :wink: ! (few mockup tools http://mashable.com/2012/06/07/mockup-tools/)

_=> LINK TO PERRINE TEMPLATE_

And finally you will have the total freedom to use plugins or framework (e.g.: http://getbootstrap.com/ ; http://foundation.zurb.com/ ; https://getmdl.io/)

## Features

That's a chat, let people discuss together, of course.

* First make one big global channel, and after allow other channel like private discussions ;
* Let users choose a pseudo and maybe defined an avater => https://fr.gravatar.com/ ;
* Let people send emoji smiley / link / pictures / youtube video / user tags / etc.. (you will use REGEX) ;
* Make everything looks great and don't forget the app have to be responsive, think about how it will look on mobile devices !

## Design

Here few advices and tricks to help you to work together on the same project code :

First work together on global design, next split the team, between for example Backend and Frontend developers, the good idea is to use demo function, e.g. :

```javascript
var sendMessage = function (message) {
    console.log("DEMO: sendMessage: " + message);
};

var retreiveMessages = function () {
    var messages = [
        { pseudo: "Romeo", message : "Ô Roméo ! Roméo ! pourquoi es-tu Roméo ? Renie ton père et abdique ton nom ; ou, si tu ne le veux pas, jure de m’aimer, et je ne serai plus une Capulet." },
        { pseudo: "Juliette", message : "Dois-je l’écouter encore ou lui répondre ?" }
    ];
    console.log("DEMO: retreiveMessages :" + messages);
    return messages;
};
```

## Ressources

REGEX (REGular EXpressions) https://en.wikipedia.org/wiki/Regular_expression ! You can check it online with https://regex101.com/ & http://regexr.com/ and practice a bit here: https://www.hackerrank.com/domains/regex/

AJAX https://en.wikipedia.org/wiki/Ajax_%28programming%29 ! You can read the official jQuery documentation https://api.jquery.com/jquery.get/ & http://api.jquery.com/jquery.ajax/ and a bit of OpenClassrooms https://openclassrooms.com/courses/simplifiez-vos-developpements-javascript-avec-jquery/premiers-pas-avec-ajax & https://openclassrooms.com/courses/un-site-web-dynamique-avec-jquery/le-fonctionnement-de-ajax
