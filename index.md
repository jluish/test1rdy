<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta name="viewport" content="width=device-width, user-scalable=no">
    <title>Tickets</title>
    <link href="css/font-awesome.css" rel="stylesheet" />
    <link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css?family=Roboto+Condensed:400,700|Roboto:400,700,900" rel="stylesheet">
</head>  
<style>

body{
    margin: auto;
    font-family: "Roboto Condensed";
}
/*header stuff*/
header{
    padding-top: 0;
    width: 100%;
    background-color: black;
    color:white;
    height:32px;
    border-bottom: 3px solid white;
}
header h2{
    float: left;
    padding-left: 2%;
    margin-top: 2px;
}
header button{
    height:100%;
    background-color: black;
    color:white;
    float: right;
    border:none;
    border-left: 1px solid white;
    font-size: 20px;
}
#btnBuyTickets{
    width: 80%;
    height:15%;
    background-color: white;
    color:black;
    border:none;
    border-bottom: 2px solid black;
    padding:0 10% 10px 10%;
    position: absolute;
    font-weight: 800;
    font-size: 28px;
    top:6%;
}
.hButtons{
    text-align: center;
    display: none;
    width: 19.33%;
    color: black;
    font-weight: bold;
    float: left;
    background-color: white;
    border-left: 1px solid black;
}
#creativeBtn{
    width: 30%;
}
#ticketsBtn{
    background-color: black;
    color: white;
}
/*main stuff*/
main{
    width: 100%;
    text-align: center;
}
main table{
    border:14px solid white;
    padding-top:100px;
    display: inline-table;
}
main table th{
    border:7px solid white;
}
main table td{
    border:7px solid white;
}
#desktopTable{
    display: none;
    border-collapse:collapse;
}
#desktopTable button{
    border: none;
    font-weight: bold;
    height: 40px;
    width: 178px;
    margin-top: 10px;
}
.fRow{
    text-align: left;
    padding-bottom: 160px;
}
.allTickets{
    width: 147px;
    float: left;
}
#desktopTable th{
    border: 1px;
    border:none !important;
}
#desktopTable td{
    border: 1px;
    border-top: 1px solid white;
    height:46px;
}
#desktopTable .White, #desktopTable .Black{
    border-top: 1px solid rgb(115,115,115);
}
.desc{
    width:400px;
    text-align: left;
    font-weight: bold;
    padding-left: 10px;
    border:none !important;
}
.ticketInfo .fa{
    font-size: 60px;
}
.price{
    font-size: 45px;
    font-weight: 800;
}
.seal{
    position: absolute;
    margin-left: 5px;
    float:right;
    margin-top: -10px;
    width:1px;
    border:1px solid black;
    display:block;
    text-align: center;
    font-size: 7px;
    font-weight: bold;
    border-radius: 50%;
    width:38px;
    height:38px;
}
.ticketInfo{
    height: 221px;
    width: 207px;
    background-color: yellow;
    font-size: 21px;
}
.buyBtn{
    height:35px;
    width: 207px;
}
.featInfo{
    height: 129px;
    width: 207px;
    background-color: white;
}
.buyBtn button{
    border:none;
    width:100%;
    height: 100%;
    font-weight: bold;
}
ul{
    left:-10px;
    position: relative;
    text-align: left;
    font-weight: lighter;
    font-size: 14px;
}
/*footer shtuffz*/
footer{
    width: 100%;
    text-align: center;
    height: 260px;
}
footer h1{
    display: block;
    font-size: 41px;
}
footer nav{
    display: inline-table;
    padding-bottom: 25px;
}
footer p{
    font-weight: bold;
    display: none;
}
.alertInput{
    border: 3px solid black;
    font-weight: bold;
    text-align: center;
    height: 42px;
    -webkit-text-fill-color: black;
}
#btnAlert{
    height: 47px;
    width: 172px;
    border-top: none;
}
#firstName{
    width: 211px;
}
#lastName{
    width:211px;
    border-left: none;
}
#eMail{
    width: 256px;
    border-top: none;
    border-right: none;
}
/*menu (tappin' da top right button)*/
#phantomHeader{
    width: 100%;
    background-color: black;
    color:white;
    height:32px;
}
#mnbtns{
    position: absolute;
    top:32px;
    width: 100%;
}
#menu{
    display: none;
    top:0;
    position: fixed;
    width: 100%;
    height: 100%;
    background-color: white;
    z-index: 5;
}
.headerBtn{
    height: 42px;
    border:none;
    border-bottom: 2px solid black;
    width: 100%;
    display: block;
    font-weight: bold;
}
/*colorz!*/
.Gray{
    background-color: rgb(230,231,233);
    color:black;
}
.Yellow{
    background-color: rgb(255,242,0);
    color:black;
}
.White{
    background-color: white;
    color:black;
}
.Black{
    background-color: black;
    color:white;
}
/*Desktop Reolution Settings*/
@media screen and (min-width: 1000px) {
    #menu{
        visibility: hidden;
    }

    footer h1{
        font-size: 50px;
    }
    footer p{
        display: initial;
    }
    .alertInput{
        border: none;
        width: 25%;
    }
    #firstName{
        border:3px solid black;
    }
    #btnAlert{
        border:3px solid black;
        border-left: none;
        height:50px;
    }
    #lastName,#eMail{
        border:3px solid black;
        border-left: none;
    }
    #btnBuyTickets{
        display: none;
    }
    header{
        background-color: white;
        color: black;
        height:37px;
        border-bottom: 3px solid black;
    }
    header h2{
        font-size: 26px;
        width:10%;
    }
    header button{
        display: none;
    }
    .hButtons{
        display: initial;
    }
    main table{
        display: none;
    }
    #desktopTable{
        display: initial;
    }
}
</style>
<body>
    <header><h2>-ING</h2>
        <button  id="btnMenu"><i class="fa fa-navicon"></i></button>
        <button class="hButtons" id="creativeBtn">CREATIVE FESTIVAL 2017</button>
        <button class="hButtons" id="pastBtn">PAST EVENTS</button>
        <button class="hButtons" id="storyBtn">OUR STORY</button>
        <button class="hButtons" id="ticketsBtn">BUY TICKETS</button>  
        <button id="btnBuyTickets">BUY </br>TICKETS</button>       
    </header>
    <div id="menu">
        <header id="phantomHeader"><h2>-ING</h2>
            <button id="menuClose"><i class="fa fa-close"></i></button>     
        </header>
        <div id="mnbtns">
            <button class="headerBtn White Black">BUY TICKETS</button>
            <button class="headerBtn White">CREATIVE FESTIVAL 2017</button>
            <button class="headerBtn White">PAST EVENTS</button>
            <button class="headerBtn White">OUR STORY</button>
            <button class="headerBtn White">FAQ</button>
            <button class="headerBtn White">ARTISTS Q&amp;A</button>
            <button class="headerBtn White">CONTACT</button>
        </div>
    </div>
    <main>
        <!--desktop table-->
        <table id="desktopTable">
            <tr>
                <th class="White fRow">
                    All tickets are subject to change</br>
                    <button class="Black allTickets">ALL TICKETS</button>
                </th>
                <th class="ticketInfo Gray">
                    <i class="fa fa-ticket fa-rotate-90"></i></br>
                    3 DAY</br>PASS</br>
                    </br>
                    </br>
                    <label class="price">$270</label><sup> USD</sup>
                </th>
                <th class="ticketInfo Yellow">
                    <i class="fa fa-ticket"></i></br>
                    ALL INCLUSIVE</br>TICKET</br>
                    </br>
                    <label class="seal"></br>BEST</br>VALUE</label>
                    </br>
                    <label class="price">$595</label><sup> USD</sup>
                </th>
                <th class="ticketInfo White">
                    <i class="fa fa-pencil"></i></br>
                    WORKSHOP</br>TICKET</br>
                    </br>
                    <label class="seal"></br>MOST</br>POPULAR</label>
                    </br>
                    <label class="price">$325</label><sup> USD</sup>
                </th>
                <th class="ticketInfo Black">
                    <i class="fa fa-star"></i></br>
                    INFLUENCER</br>TICKET</br>
                    </br>
                    </br>
                    <label class="price">$1350</label><sup> USD</sup>
                </th>
            </tr>
            <tr class="desktopRow">
                <td class="desc Gray">CREATIVE MARKET <i class="fa fa-question-circle-o"></i></td>
                <td class="Gray"><i class="fa fa-circle"></i></td>
                <td class="Yellow"><i class="fa fa-circle"></i></td>
                <td class="White"></td>
                <td class="Black"><i class="fa fa-circle"></i></td>
            </tr>
            <tr class="desktopRow">
                <td class="desc White">TALKS (BY SPEAKERS) <i class="fa fa-question-circle-o"></i></td>
                <td class="Gray"><i class="fa fa-circle"></i></td>
                <td class="Yellow"><i class="fa fa-circle"></i></td>
                <td class="White"></td>
                <td class="Black"><i class="fa fa-circle"></i></td>
            </tr>
            <tr class="desktopRow">
                <td class="desc Gray">1 CAREER CORNER SESSION <i class="fa fa-question-circle-o"></i></td>
                <td class="Gray"><i class="fa fa-circle"></i></td>
                <td class="Yellow"><i class="fa fa-circle"></i></td>
                <td class="White"></td>
                <td class="Black"><i class="fa fa-circle"></i></td>
            </tr>
            <tr class="desktopRow">
                <td class="desc White">1 WORKSHOP SESSION <i class="fa fa-question-circle-o"></i></td>
                <td class="Gray"></td>
                <td class="Yellow"><i class="fa fa-circle"></i></td>
                <td class="White"><i class="fa fa-circle"></i></td>
                <td class="Black"><i class="fa fa-circle"></i></td>
            </tr>
            <tr class="desktopRow">
                <td class="desc Gray">NETWORKING SESSION <i class="fa fa-question-circle-o"></i></td>
                <td class="Gray"></td>
                <td class="Yellow"><i class="fa fa-circle"></i></td>
                <td class="White"></td>
                <td class="Black"><i class="fa fa-circle"></i></td>
            </tr>
            <tr class="desktopRow">
                <td class="desc White">GOODIE BAG <i class="fa fa-question-circle-o"></i></td>
                <td class="Gray"></td>
                <td class="Yellow"><i class="fa fa-circle"></i></td>
                <td class="White"></td>
                <td class="Black"><i class="fa fa-circle"></i></td>
            </tr>
            <tr class="desktopRow">
                <td class="desc Gray">DINNER WITH SPEAKERS <i class="fa fa-question-circle-o"></i></td>
                <td class="Gray"></td>
                <td class="Yellow"></td>
                <td class="White"></td>
                <td class="Black"><i class="fa fa-circle"></i></td>
            </tr>
            <tr class="desktopRow">
                <td class="desc White">LISTING ON -ING WEBSITE <i class="fa fa-question-circle-o"></i></td>
                <td class="Gray"></td>
                <td class="Yellow"></td>
                <td class="White"></td>
                <td class="Black"><i class="fa fa-circle"></i></td>
            </tr>
            <tr class="desktopRow">
                <td class="desc Gray">SPEAKERS' ROOM ACCESS <i class="fa fa-question-circle-o"></i></td>
                <td class="Gray"></td>
                <td class="Yellow"></td>
                <td class="White"></td>
                <td class="Black"><i class="fa fa-circle"></i></td>
            </tr>
            <tr class="btnRow">
                <td></td>
                <td><button class="deskBuyTicket Gray">3 DAY PASS</button></td>
                <td><button class="deskBuyTicket Yellow">ALL INCLUSIVE TICKET</button></td>
                <td><button class="deskBuyTicket Gray">WORKSHOP TICKET</button></td>
                <td><button class="deskBuyTicket Black">INFLUENCER TICKET</button></td>
            </tr>
        </table>
        <!--mobile table-->
        <table>
            <tr>
                <th class="ticketInfo Gray">
                    <i class="fa fa-ticket fa-rotate-90"></i></br>
                    3 DAY</br>PASS</br>
                    </br>
                    </br>
                    <label class="price">$270</label><sup> USD</sup>
                </th>
                <th class="ticketInfo Yellow">
                    <i class="fa fa-ticket"></i></br>
                    ALL INCLUSIVE</br>TICKET</br>
                    </br>
                    <label class="seal"></br>BEST</br>VALUE</label>
                    </br>
                    <label class="price">$595</label><sup> USD</sup>
                </th>
            </tr>
            <tr>
                <td class="buyBtn"><button class="Gray"><label class="mobile">BUY TICKET</label></button></td>
                <td class="buyBtn"><button class="Yellow"><label class="mobile">BUY TICKET</label></button></td>
            </tr>
            <tr>
                <td class="featInfo">
                    <ul>
                        <li>Creative Market</li>
                        <li>Talks (By Speakers)</li>
                        <li>1 Career Corner Session</li>
                    </ul>
                </td>
                <td class="featInfo">
                    <ul>
                        <li>Creative Market</li>
                        <li>Talks (By Speakers)</li>
                        <li>1 Career Corner Session</li>
                        <li>1 Workshop Session</li>
                        <li>Networking Session</li>
                        <li>Goodie Bag</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <th class="ticketInfo White">
                    <i class="fa fa-pencil"></i></br>
                    WORKSHOP</br>TICKET</br>
                    </br>
                    <label class="seal"></br>MOST</br>POPULAR</label>
                    </br>
                    <label class="price">$325</label><sup> USD</sup>
                </th>
                <th class="ticketInfo Black">
                    <i class="fa fa-star"></i></br>
                    INFLUENCER</br>TICKET</br>
                    </br>
                    </br>
                    <label class="price">$1350</label><sup> USD</sup>
                </th>
            </tr>
            <tr>
                <td class="buyBtn">
                    <button class="Gray"><label class="mobile">BUY TICKET</label></button>
                </td>
                <td class="buyBtn">
                    <button class="Black"><label class="mobile">BUY TICKET</label></button>
                </td>
            </tr>
            <tr>
                <td class="featInfo">
                    <ul>
                        <li>1 Workshop Session</li>
                    </ul>
                </td>
                <td class="featInfo">
                    <ul>
                        <li>Creative Market</li>
                        <li>Talks (By Speakers)</li>
                        <li>1 Career Corner Session</li>
                        <li>1 Workshop Session</li>
                        <li>Networking Session</li>
                        <li>Goodie Bag</li>
                        <li>Dinner with Speakers</li>
                        <li>Listing on -ING Website</li>
                        <li>Speaker's Room Access</li>
                    </ul>
                </td>
            </tr>
        </table>
    </main>
    <footer>
        <h1>SIGN UP FOR FESTIVAL ALERTS</h1></br>
        <nav>
            <input type="text" id="firstName" placeholder="FIRST NAME" class="alertInput White"/>
            <input type="text" id="lastName" placeholder="LAST NAME" class="alertInput"/>
            <input type="text" id="eMail" placeholder="EMAIL" class="alertInput"/>
            <button type="submit" id="btnAlert" class="alertInput Yellow">SIGN UP</button>
        </nav></br>
        <p>We promise to only email you when we have something important, we love our inboxes clean too!</p>
    </footer>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
    <script>
        $(document).ready(function(){
            $("#btnMenu").on("click",function(){
                $("#menu").show();
                $("html").css({"overflow":"hidden"});
            });
            $("#menuClose").on("click",function(){
                $("#menu").hide();
                $("html").css({"overflow":"auto"});
                
            });
            $(window).resize(function(){
                if($(window).width()>=1000){
                    $("#menu").hide();
                    $("html").css({"overflow":"auto"});
                }
            });

        });
    </script>
</body>
</html>
