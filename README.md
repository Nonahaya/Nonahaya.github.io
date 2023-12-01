# Test Api Release

> what About dummy Api
dummy api use [mockapi.io](https://mockapi.io)

>How to Use [mockai.io](https://mockapi.io)

   
    //javaScript
    const url = "https://*somthing.mockapi.io/api/v1/Blog";
    (async () => {
	    const res = await fetch(url+"/*id");
	    if(!res.ok){
	    throw  new  Error("somthing Error");
	    };
	    const json = await res.json();
	    const title = await json.BlogTitle;
		const body = await json.BlogBody;
		return {title,body}
    })();

*somthing =  [mockai.io](https://mockapi.io) private key 
*id = Blog Id 
