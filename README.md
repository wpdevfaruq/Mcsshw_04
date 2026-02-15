# Mcsshw_04


*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

.header{
    width:100%;
    background:#111;
    padding:15px 0;
    position:sticky;
    top:0;
    z-index:1000;
}

.container{
    width:90%;
    margin:auto;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.logo a{
    color:#fff;
    font-size:24px;
    font-weight:bold;
    text-decoration:none;
}

.logo span{
    color:#ff4d4d;
}

.navbar ul{
    list-style:none;
    display:flex;
}

.navbar ul li{
    margin:0 15px;
}

.navbar ul li a{
    color:#fff;
    text-decoration:none;
    font-size:16px;
    transition:0.3s;
}

.navbar ul li a:hover{
    color:#ff4d4d;
}

.search-box{
    display:flex;
}

.search-box input{
    padding:5px 10px;
    border:none;
    outline:none;
}

.search-box button{
    padding:6px 12px;
    border:none;
    background:#ff4d4d;
    color:#fff;
    cursor:pointer;
}

.menu-toggle{
    display:none;
    color:#fff;
    font-size:24px;
    cursor:pointer;
}

/* Responsive */
@media(max-width:768px){

    .navbar{
        position:absolute;
        top:70px;
        left:0;
        width:100%;
        background:#222;
        display:none;
        flex-direction:column;
        text-align:center;
    }

    .navbar ul{
        flex-direction:column;
    }

    .navbar ul li{
        margin:15px 0;
    }

    .search-box{
        display:none;
    }

    .menu-toggle{
        display:block;
    }
}

