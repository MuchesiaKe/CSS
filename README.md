body{
background-color:#24414e;
height:100%;
margin:0px;
text-align:center;
}
.menu ul{
	display:flex;
	justify-content:center;
	background-color:maroon;
	height:100px;
	align-items:center;
}

.menu li{
list-style:none;
width:10%;

}
li:hover{
	background-color:white;
	height:100%;
}
/*
.menu li:nth-child(1){
	justify-content:start;
}*/
.logo{

}
h1{
    color: white;
    text-align: center;
    font-size: 2em;
}
 .main-content{

	 color:#f7ecec;
	padding: 2em 1.5em;
	padding-top:10%;
	height:100%;
	
 }
 .main-wrapper{
	 min-height:100vh;
	 font-size:1.3em;
	 line-height:1.5em;
 }
 button{
	
	display: inline-block;
    width: 100px;
    height: 50px;
    background-color: #6b0e20;
	color: #0fe685;
 }
 .button a{
	text-decoration:none; 
	color: #0fe685;
 }
 button:hover{
	 background-color:white;
	 color:black;
	 border-radius:10px;
 }
 .button{
   text-align:center;
 }
.back{
    background-image: url("anon-back.jpg");
    background-size: cover;
    width: 100%;
	height:100%;
  	position:absolute;
	z-index:-1;
	opacity:0.2;
}

.board{
	background-color:#292b44;
	width:100%
	height:300px;
	font-size:1.1em;
	padding:2em 3em;
}

.board-top{
display:flex; 
align-content:center;
justify-content:center;
}

.topline{
width:10%;
height:5px;
background-color:maroon;
margin:50px;

}
img{
	width:100%;
	height:auto;
}
.members p{
	color:white;
}
.members h1{
	color:green;
}
.members{
	margin:5em 0;
	border:2px solid white;
background-color: #500449;
}
.about{
    background-color: #573d65;
margin:0px;
padding:0 2em 50px 2em;
font-size:1.2em;

}
.underline{
	width:200px;
height:2px;
background-color:maroon;
margin:auto;
padding:0px;
}

.about h1{
padding:50px 0 0 0;	
}
.contact{
	min-height:50vh;
	background-color:grey;
	width:80%;
	border: 1px solid black;
	border-radius:10%;
	margin:auto;
	margin-bottom:5%;
	margin-top:5%;
}
.contact label{
	display:flex;
	flex-direction:column;
	color:maroon;
	font-weight:bold;
}
textarea{
	height:150px;
	width:70%;
}
input , select, textarea{
	width:50%;
}
.form{
margin:0 0 1em 0;	
}
.footer{
	min-height:10vh;
	background-color:black;
	color:white;
	padding:5% 0;
}

.contacts{
	background-color:#042510;
	color:burlywood;
	padding:3em 0;
}
span{
	color:red;
}




/*Grid properties*/
.container{
	display:grid;
	grid-template-columns: 1fr repeat(2, minmax(auto, 25em)) 1fr;
}

section{
	grid-column:2/4;
}
.board{
	
}
.contacts{
	
}
.contact{
	
}
.footer{
	
}
