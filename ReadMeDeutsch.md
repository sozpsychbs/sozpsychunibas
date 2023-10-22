define(['pipAPI', 'https://cdn.psychologie.unibas.ch/minnojs/quiat-9.js'], function(APIConstructor, iatExtension){
var API = new APIConstructor();

	
	return iatExtension({
		category1 : {
			name : 'Männer', //Will appear in the data.
			title : {
				media : {word : 'Männer'}, //Name of the category presented in the task.
				css : {color:'#336600','font-size':'1.8em'}, //Style of the category title.
				height : 4 //Used to position the "Or" in the combined block.
			}, 
			stimulusMedia : [ //Stimuli content as PIP's media objects
    		    {word : 'Christian'},
	            {word : 'Michael'},
	            {word : 'Sebastian'},
	            {word : 'Stefan'},
	            {word : 'Jan'},
	            {word : 'Daniel'}
    			
			], 
			//Stimulus css (style)
			stimulusCss : {color:'#336600','font-size':'2.3em'}
		},	
		category2 :	{
			name : 'Frauen', //Will appear in the data.
			title : {
				media : {word : 'Frauen'}, //Name of the category presented in the task.
				css : {color:'#336600','font-size':'1.8em'}, //Style of the category title.
				height : 4 //Used to position the "Or" in the combined block.
			}, 
			stimulusMedia : [ //Stimuli content as PIP's media objects
    		    {word : 'Julia'},
	            {word : 'Katrin'},
	     	    {word : 'Stefanie'},
	   	    {word : 'Melanie'},
	 	    {word : 'Sandra'},
        	    {word : 'Anja'}
	     
    			], 
			//Stimulus css
			stimulusCss : {color:'#336600','font-size':'2.3em'}
		},
  		attribute1: 
    		{
      			name : 'Durchsetzungsvermögen',
	 		title : {
    				 media : {word : 'Durchsetzungsvermögen'},
	 			 css : {color: '#0000FF', 'font-size': '1.8em'}, 
      				 height : 4
	   	},
     		stimulusMedia : [ //Stimuli content as PIP's media objects
       		    {word : 'unabhängig'},
	            {word : 'selbstbewusst'},
	     	    {word : 'kompetitiv'},
	   	    {word : 'belastbar'},
	 	    {word : 'tatkräftig'},
        	    {word : 'entscheidungsfreudig'},
	     	    {word : 'hartnäckig'},
	   	    {word : 'fühlt sich überlegen'}
	 	],
   		stimulusCss : {color:'#0000FF','font-size': '2.3em'}
     		},
       		attribute2 : 
	 	{
   			name : 'Mitgefühl',
      			title : {
	 			 media : {word : 'Mitgefühl'},
      				 css : {color: '#0000FF', 'font-size': '1.8em'},
	   			 height : 4
		
		},
		stimulusMedia : [//Stimuli content as PIP's media objects
			{word : 'hilfsbereit'},
	                {word : 'einfühlsam'},
	     	        {word : 'warmherzig'},
			{word : 'liebenswürdig'},
	   	        {word : 'emotional'},
	 	        {word : 'hingebungsvoll'},
        	        {word : 'gutmütig'},
	     	        {word : 'verständnisvoll'}
	   	        
    		],
      		stimulusCss : {color:'#0000FF','font-size': '2.3em'},
		},

 
	remindError: true,
	remindErrorText: '<p align="center" style=font-size:0.6em; font-family:arial">' +
	'Wenn Sie einen Fehler machen, erscheint ein rotes <font color="#ff0000"><b>X</b></font> ' +
	'Drücken Sie eine andere Taste, um fortzufahren. <p/>' +
				'<u>Gehen Sie so schnell wie möglich</u> und gleichzeitig so genau wie möglich vor.<br/><br/></p>'+
				'<p align="center">Drücken Sie die <b>Leertaste</b> wenn Sie bereit sind, zu beginnen.</font></p></div>',

 	leftKeyText : 'Drücken Sie "E" für',
	rightKeyText : 'Drücken Sie "I" für',
 	orText : 'oder',
  	finalText : 'Drücken Sie die Leertaste, um mit der nächsten Aufgabe fortzufahren.'

	};


        
		 
	});
});
