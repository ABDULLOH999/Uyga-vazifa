<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Word press2</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="continer">
        <div class="blok1">
            <img src="photo.jpg.png" alt="">
            <h5 class="q1">WordPress интенсив</h5>
            <h3>Создать свой сайт на WordPress </h3>
            <h1>это просто! </h1>
            <hr class="a1">
            <hr class="a2">
            <h3 class="a3">Куда сложнее сделать это правильно!</h3>
            <h5 class="q2">Ежедневно в России появляется более 5 000 новых сайтов. <br>
             И только единицы из них становятся популярными и приносят ощутимую прибыль. В чем секрет? В чем формула <br>
                  успеха? Узнайте на предстоящем двухдневном <font>БЕСПЛАТНОМ</font> интенсиве!</h5>
                  <button class="bt">Записаться на интенсив!</button><br><br>
                  <h6>узнать больше об интенсиве</h6><br><br>
                  <img src="down.png" alt=""  class="down">
        </div>
        <div class="blok2">
            <h2>Что вас ждет в нашем интенсиве?</h2>
            <hr class="hr1">
            <h6 class="t1">2 бесплатных полноценных обучающих вебинара, где:</h6>
            <div class="logo">
                <div class="one">
                    <img src="waiting_1.png" alt="">
                    <h6>Всего за два бесплатных вебинара мы научим вас, <br>
                        как создать свой сайт на WordPress. </h6>

                </div>
                <div class="one">
                    <img src="waiting_2.png" alt="">
                    <h6>Покажем, как правильно оптимизировать сайт и <br>
                         сделать его привлекательным для поисковых <br>
                          систем. Только свежая, профессиональная и <br>
                           актуальная информация! </h6>
                </div>
                <div class="one">
                    <img src="waiting_3.png" alt="">
                    <h6>Вы узнаете, что такое «хорошая индексация», <br>
                         «высокая посещаемость», «стабильный прирост <br>
                          посетителей», «ТОП по запросам» и, что намного <br>
                           важнее, как добиться всех этих показателей! </h6>
                </div>
            </div>
        </div>
        <div class="blok3">
            <div class="left">
                <img src="woman_bg.png" alt="">
            </div>
            <div class="right">
                <h2>Что такое оптимизация и зачем она нужна?</h2>
                <h5>На просторах интернета несчетное количество действующих и даже заброшенных сайтов. <br>
                     Большинство из них совпадает не только по категориям, но и по содержанию.  <br><br>

                    Представьте себе тысячи сайтов, на которых тем или иным образом предоставляется одна и <br>
                     та же информация или продается одна и та же услуга. И попасть на эти сайты можно лишь по <br>
                      тематическим запросам в поисковых системах. <br> br'

                    Но как вам быть, если ваш сайт похож на сотню или тысячу таких же, а на одной странице <br>
                     гугла или яндекса всего 10 позиций? Как привести посетителей страницы своего ресурса? <br>
                      Именно для этого и нужна оптимизация – для вывода вашего сайта на первую страницу <br>
                       поиска! <br><br>

                    Мы научим вас, как сделать ваш сайт привлекательным для поисковых систем и <br>
                     посоветуем, как вывести его на первые страницы, обходя всех конкурентов.</h5>
            </div>
        </div>
        <div class="log"><img src="icon.png" alt=""></div>
        <div class="blok4">
            <img src="Rectangle.png" alt=""><br><br><br>
            <h5>Для всех участников интенсива предусмотрены бонусы и подарки. Нажимайте <br>
                 на кнопку ниже, принимайте участие в вебинарах и забирайте свой приз по <br>
                  окончании обучения!</h5>
                  <button class="bt">Записаться на интенсив!</button>
        </div>
        <div class="blok5">
            <img src="first.png" class="q3" alt=""><br><br><br>
            <h2>Первый вебинар состоится:</h2><br>
            <h2 class="q4">10 сентября в 20:00 по Москве</h2><br>
            <h3>Успейте записаться, количество мест ограничено!</h3>
        </div>
        <div class="log1">
            <h5>Служба поддержки  |  Политика конфиденциальности <br>
                Позвоните нам 8-800-555-01-21</h5>
        </div>
    </div>
</body>
</html> 


css


@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.continer{
    font-family: 'Roboto';
    text-transform: capitalize;
}
.blok1{
    background-image: url(main_bg.png);
    width: 1345px;
    height: 800px;
    left: 0px;
    top: 2px;
}
.blok1 .q1{
    margin-top: 9.5px;
    margin-bottom: 53px;
    color: white;
    padding-left: 580px;
}
.blok1 img{
    padding-left: 600px;
}
.blok1 h3{
    color: #F9BF3B;
    font-weight: 900;
    font-size: 41px;
    line-height: 41px;
    margin-left: 350px;
}
.blok1 h1{
    margin-top: 20.5px;
    margin-bottom: 20.5px;
    font-weight: 900;
    font-size: 80px;
    line-height: 80px;
    color: #ffffff;
    margin-left: 450px;
}
.a1{
    margin-top: -60px;
    width: 292px;
    height: 2px;
    margin-left: 120px;
}
.a2{
    width: 292px;
    height: 2px;
    margin-left: 950px;
}
.a3{
    margin-top: 50.5px;
}
.q2{
    margin-left: 50px;
    margin-top: 22.5px;
    font-weight: 300;
    font-size: 21px;
    line-height: 28px;
    /* or 133% */
    color: white;
    text-align: center;
}
font{
    font-weight: 900;
    color: #F9BF3B;
}
.bt{
    width: 313px;
    height: 72px;
    background: linear-gradient(0deg, #2798B9 0%, #3AB6DA 100%);
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.4);
    margin-top: 72px;
    margin-left: 540px;
}
h6{
    font-weight: 100;
    font-size: 15px;
    line-height: 24px;
    margin-top: 70px;
    margin-left: 620px;
}
.t1{
    margin-top: 18.5px;
    margin-left: 430px;
    font-weight: 400;
    font-size: 23px;
    line-height: 20px;
    /* identical to box height, or 87% */
    color: #4A4A4A;
    display: flex;
    align-items: center;
    text-align: center;
}
.down{
    margin-left: 105px;
}


.blok2 h2{
    margin-top: 144px;
    margin-left: 440px;
    font-weight: 400;
    font-size: 30px;
    line-height: 30px;
    /* or 100% */
    color: #252525;
    display: flex;
    align-items: center;
    text-align: center;
    text-transform: uppercase;
}
.hr1{
    width: 220px;
    height: 7px;
    margin-top: 18px;
    margin-left: 610px;
    background: #F9BF3B;
}
.logo{
    margin-top: 18.5px;
    width: 1345px;
    padding-top: 46px;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(100px, auto));
    height: 607px;
    background: #EFEFEF;
}
.one h6{
    margin-top: 26px;
    margin-left: 10px;
    margin-bottom: 75px;
}
.blok3{
    display: flex;
    flex-direction: row;
}
.right h2{
    margin-left: -300px;
    margin-top: 108px;
    font-weight: 900;
    font-size: 30px;
    line-height: 30px;
    /* identical to box height, or 100% */

    text-transform: uppercase;
    color: #299CBD;
}
.right h5{
    margin-top: 25px;
    margin-left: -300px;
    font-weight: 300;
    font-size: 17px;
    line-height: 20px;
    /* or 159% */
    display: flex;
    align-items: center;
    color: #4A4A4A;
}
.log img{
    width: 1345px;
    height: 447px;
}
.blok4{
    width: 1345px;
    height: 631px;
    background: #EFEFEF;
    margin-bottom: 89px;
}
.blok4 img{
    margin-top: 88px;
    margin-left: 560px;
}
.blok4 h5{
    margin-left: 180px;
    font-weight: 400;
    font-size: 25px;
    line-height: 43px;
    /* or 143% */
    display: flex;
    align-items: center;
    text-align: center;
    color: #252525;
}
.blok4 .bt{
    margin-left: 500px;
}

.blok5{
    background: white;
}
.blok5 .q3{
    margin-left: 500px;
}
.blok5 h2{
    margin-left: 450px;
    font-weight: 400;
    font-size: 30px;
    line-height: 30px;
    /* identical to box height, or 100% */
    display: flex;
    align-items: center;
    text-align: center;
    text-transform: uppercase;
    color: #252525;
}
.q4{
    margin-left: 450px;
    font-weight: 400;
    font-size: 30px;
    line-height: 30px;
    /* identical to box height, or 100% */
    display: flex;
    align-items: center;
    text-align: center;
    text-transform: uppercase;
    color: #299CBD;
}
.blok5 h3{
    margin-left: 450px;
    font-weight: 400;
    font-size: 20px;
    line-height: 20px;
    /* identical to box height, or 87% */
    display: flex;
    align-items: center;
    text-align: center;
    color: #4A4A4A;
    margin-bottom: 50.5px;
}
.log1{
    width: 1345px;
    height: 169px;
    background: #1A1A1A;
}
.log1 h5{
    margin-left: 500px;
    padding-top: 57px;
    font-weight: 300;
    font-size: 15px;
    line-height: 21px;
    /* or 140% */
    display: flex;
    align-items: center;
    text-align: center;
    text-decoration-line: underline;
    color: #888888;
} 
