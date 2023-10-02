define(['pipAPI', 'https://cdn.jsdelivr.net/gh/baranan/minno-tasks@0.*/IAT/qualtrics/quiat9.js'], function(APIConstructor, iatExtension){
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
      			name : 'Home words',
	 		title : {
    				 media : {word : 'Home Words'},
	 			 css : {color: '#0000FF', 'font-size': '1.8em'}, 
      				 height : 4
	   	},
     		stimulusMedia : [ //Stimuli content as PIP's media objects
       		    {word : 'Staubsaugen'},
	            {word : 'Küche'},
	     	    {word : 'Ehe'},
	   	    {word : 'Wäsche'},
	 	    {word : 'Eltern'},
        	    {word : 'Kinder'},
	     	    {word : 'Pflegen'},
	   	    {word : 'Haushalt'}
	 	],
   		stimulusCss : {color:'#0000FF','font-size': '2.3em'}
     		},
       		attribute2 : 
	 	{
   			name : 'Career words',
      			title : {
	 			 media : {word : 'Career words'},
      				 css : {color: '#0000FF', 'font-size': '1.8em'},
	   			 height : 4
		
		},
		stimulusMedia : [//Stimuli content as PIP's media objects
			{word : 'Büro'},
	                {word : 'Karriere'},
	     	        {word : 'Einkommen'},
	   	        {word : 'Arbeit'},
	 	        {word : 'Unternehmen'},
        	        {word : 'Beruf'},
	     	        {word : 'Fachkraft'},
	   	        {word : 'CEO'}
    		],
      		stimulusCss : {color:'#0000FF','font-size': '2.3em'}
		} 
	});
});
