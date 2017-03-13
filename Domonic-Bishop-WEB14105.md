# Vimeo upload: https://vimeo.com/208009580
# Content strategy: https://docs.google.com/document/d/1DXC1Aw8LXL5nuHHXyxaIqML4rxYkouXBIAcW5BJgApg/edit?usp=sharing
# Research: https://docs.google.com/document/d/1YN14YWfJXK7ald6qcmAX1DxaPjnR5kpQzIz6g0xNS9E/edit?usp=sharing
# code for website (so far): 
```

<!DOCTYPE html>
<html>
    
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>GETTING STARTED WITH BRACKETS</title>
        <meta name="description" content="An interactive getting started guide for Brackets.">
        <link rel="stylesheet" href="css/style.css">
        <script src="http://s.codepen.io/assets/libs/modernizr.js" type="text/javascript"></script>
        <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">
    </head>
    <body>
        
			<section id="one" class="col-2 ss-style-roundedsplit">
				<div class="column">
					<h1>A DAY IN THE FUTURE</h1>
				</div>
            </section>
        
			<section id="two" class="col-2 ss-style-foldedcorner">
				<div class="column">
					<p>Noah listened to his teacher as best he could, trying to stop himself thinking about the rain outside, because with rain there would likely come what Noah feared more than anything else in the whole wide world. Noah’s teacher read a story to the class about how by watching what everyone does all the time “we have been able to stop anyone in the world doing anything bad ever”. This wasn’t the first time the class had heard this story, they had been told it everyday.</p>
				</div>
            </section>
            
			<section class="col-2 ss-style-foldedcorner">
				<div class="column">
					<p>Later on, when Noah had his tea and had gone to bed, what Noah had been worried about happening in the class that day began to happen, outside he could hear the lightning crashing and inside he could see it flashing through the curtains in his bedroom!</p>
				</div>
            </section>
        
            <section class="col-2 ss-style-foldedcorner">
				<div class="column">
					<p>Noah was so scared he couldn’t shut his eyes, so he did what he always did when there was lightning. Noah went to his mum and dad's room and slept with them in their bed, that was Noah’s only hope of getting to sleep that night.</p>
				</div>
            </section>
        
            <section class="col-2 ss-style-foldedcorner">
				<div class="column">
					<p>The next day at school a boy named Tom came over to Noah. Noah didn’t really like Tom, Tom’s dad worked for the police so he always acted like he was better than everyone else. Tom had a grin on his face. “I know ran to your mum and dad's bed last night Tom” said Tom, still grinning “I was on my dad's computer this morning and saw the whole thing”. Noah’s face turned red, Tom was going to tell everyone what had happened and then everyone would laugh at him forever. Everyone was going to believe Tom because everyone knew it was Tom’s dad’s job to watch everyone all the time, even when everyone went to bed...</p>
				</div>
            </section>
        
            
    </body>
</html>
```

```css
#one {
    background-image: url(../images/blue-animal.jpeg)
}

#two {
    background-image: url(../images/blue-animal.jpeg)
}

#three {
    background-image: url(../images/blue-animal.jpeg)
}

#four {
    background-image: url(../images/blue-animal.jpeg)
}

#five {
    background-image: url(../images/blue-animal.jpeg)
}

.container svg {
	display: block;
}

section {
	position: relative;
	padding: 4em 10%;
    padding-bottom: 10em;
	text-align: center;
    font-family: 'Merriweather', serif;
}

p {
	color: black;
	font-size: 1.2em;
	line-height: 1.8;
}

h1 {
    font-size: 2em;
    font-variant: small-caps;
}

.column {
    padding-bottom: 10em
}

section::before,
section::after {
	position: absolute;
	content: '';
	pointer-events: none;
}

.ss-style-foldedcorner::before,
.ss-style-foldedcorner::after {
	bottom: 0px;
	width: 100px;
	height: 100px;
}

.ss-style-foldedcorner::before {
	right: 0;
	background-image: linear-gradient(315deg, #F8ECC2 50%, #F0F0F0 50%);
}

.ss-style-foldedcorner::after {
	right: 100px;
	background-image: linear-gradient(315deg, #D2C18A 50%, transparent 50%);
}
```
