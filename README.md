# image-extractor-api
a simple image extactor api



<div id="images_extractor_api" class="code">
			<h2>Image extractor api</h2>
			<div class="code-body">
				<div class="endpoint">
					<b>Endpoint : </b>
					<code>https://iysabox.com/api/images-extractor?link={link}</code>
				</div>
				<b>Request :</b>
				<code>
<pre>fetch("https://iysabox.com/api/images-extractor?link=https://example.com")
    .then(res =&gt; res.json())
    .then(data =&gt; {
	    console.log(data)
    })
</pre>
				</code>
				<b>Response :</b>
				<code>
<pre>{
    "status":"success",
    "images":[
        0 : https://www.example.com/img/image1.png"
        1 : https://www.example.com/img/image2.png"
        2 : https://www.example.com/img/image3.png"
    ]
}
</pre>
				</code>
			</div>
		</div>
