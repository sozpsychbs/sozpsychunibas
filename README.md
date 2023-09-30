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
			name : 'Sunflower', //Will appear in the data.
			title : {
				media : {word : 'Sunflower'}, //Name of the category presented in the task.
				css : {color:'#31940F','font-size':'2em'}, //Style of the category title.
				height : 4 //Used to position the "Or" in the combined block.
			}, 
			stimulusMedia : [ //Stimuli content as PIP's media objects
    		    {image : 'sunflower-6515860_1280.jpg'} 
    					], 
			//Stimulus css
			stimulusCss : {color:'#31940F','font-size':'1.8em'}
		},	

		base_url : {//Where are your images at?
			image : 'https://sozpsychbs.github.io/sozpsychunibas/'
		} 
	});
});
