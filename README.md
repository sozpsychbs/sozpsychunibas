define(['pipAPI', 'https://cdn.psychologie.unibas.ch/minnojs/quiat-9.js'], function(APIConstructor, iatExtension){
var API = new APIConstructor();

	
	return iatExtension({
		category1 : {
			name : 'Men', //Will appear in the data.
			title : {
				media : {word : 'Men'}, //Name of the category presented in the task.
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
			name : 'Women', //Will appear in the data.
			title : {
				media : {word : 'Women'}, //Name of the category presented in the task.
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
      		stimulusCss : {color:'#0000FF','font-size': '2.3em'}
		} 
	});
});
