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
      			name : 'Care-Arbeit',
	 		title : {
    				 media : {word : 'Care-Arbeit'},
	 			 css : {color: '#0000FF', 'font-size': '1.8em'}, 
      				 height : 4
	   	},
     		stimulusMedia : [ //Stimuli content as PIP's media objects
       		    {word : 'Staubsauger'},
	            {word : 'kochen'},
	     	    {word : 'putzen'},
	   	    {word : 'Wäsche'},
	 	    {word : 'einkaufen'},
        	    {word : 'bügeln'},
	     	    {word : 'nähen'},
	   	    {word : 'aufräumen'}
	 	],
   		stimulusCss : {color:'#0000FF','font-size': '2.3em'}
     		},
       		attribute2 : 
	 	{
   			name : 'Karriere',
      			title : {
	 			 media : {word : 'Karriere'},
      				 css : {color: '#0000FF', 'font-size': '1.8em'},
	   			 height : 4
		
		},
		stimulusMedia : [//Stimuli content as PIP's media objects
			{word : 'delegieren'},
	                {word : 'aufsteigen'},
	     	        {word : 'projektleitend'},
	   	        {word : 'Einkommen'},
	 	        {word : 'studieren'},
        	        {word : 'weiterbilden'},
	     	        {word : 'Expertise'},
	   	        {word : 'CEO'}
    		],
      		stimulusCss : {color:'#0000FF','font-size': '2.3em'}
		} 
	});
});
