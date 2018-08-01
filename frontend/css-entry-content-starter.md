# [CSS] Entry Content Starter CSS

```
/*===============================
	Entry Content
	===============================*/

.entry-content {
	position: relative;
}

.entry-content h2,
.entry-content h3,
.entry-content h4,
.entry-content h5,
.entry-content h6 {}

.entry-content h2 {}

.entry-content h3 {}

.entry-content h4 {}

.entry-content h5 {}

.entry-content h6 {}

.entry-content p {}

.entry-content ul,
.entry-content ol {}

.entry-content li {}

.entry-content blockquote {}

.entry-content a {
	text-decoration: underline;
}

.entry-content a:hover {
}

.entry-content a:active {
}

.entry-content strong {}

.entry-content em {}

.entry-content img,
.entry-content figure {
	max-width: 100%;
	height: auto;
	margin: 0 0 1rem;
}

.entry-content img.alignright,
.entry-content a img.alignright,
.entry-content figure.alignright {
	float: right; 
	margin: 0 0 1rem 1rem;
}

.entry-content img.alignleft,
.entry-content a img.alignleft,
.entry-content figure.alignleft {
    float: left; 
    margin: 0 1rem 1rem 0;
}

.entry-content img.aligncenter,
.entry-content a img.aligncenter,
.entry-content figure.aligncenter {
	display: block; 
	margin-left: auto; 
	margin-right: auto;
}

.entry-content figcaption {
	text-align: left; /*Decide text-align left or center */
}

.entry-content figcaption a {}

.entry-content figcaption a:hover {}

.entry-content figcaption a:active {}

.entry-content figcaption strong {}

.entry-content figcaption em {}

.entry-content iframe {
	max-width: 100%;
	height: auto;
	margin: 0 0 1rem;
}

/* ======= Entry Content - Tablet+ ======= */

@media (min-width: 768px) {

	.entry-content h2,
	.entry-content h3,
	.entry-content h4,
	.entry-content h5,
	.entry-content h6 {}

	.entry-content h2 {}

	.entry-content h3 {}

	.entry-content h4 {}

	.entry-content h5 {}

	.entry-content h6 {}

	.entry-content p {}

	.entry-content ul,
	.entry-content ol {}

	.entry-content li {}

	.entry-content blockquote {}
	
	.entry-content img.alignright,
	.entry-content a img.alignright,
	.entry-content figure.alignright {
		margin: 0 0 1rem 1.5rem;
	}
	
	.entry-content img.alignleft,
	.entry-content a img.alignleft,
	.entry-content figure.alignleft {
		float: left; 
		margin: 0 1.5rem 1rem 0;
	}

	.entry-content figcaption {}

}

/* ======= Entry Content - Desktop+ ======= */
	
@media (min-width: 992px) {

	.entry-content h2,
	.entry-content h3,
	.entry-content h4,
	.entry-content h5,
	.entry-content h6 {}

	.entry-content h2 {}

	.entry-content h3 {}

	.entry-content h4 {}

	.entry-content h5 {}

	.entry-content h6 {}

	.entry-content p {}

	.entry-content ul,
	.entry-content ol {}

	.entry-content li {}

	.entry-content blockquote {}
	
	.entry-content img.alignright,
	.entry-content a img.alignright,
	.entry-content figure.alignright {
		margin: 0 0 1rem 2rem;
	}
	
	.entry-content img.alignleft,
	.entry-content a img.alignleft,
	.entry-content figure.alignleft {
		float: left; 
		margin: 0 2rem 1rem 0;
	}

	.entry-content figcaption {}

}
```