# goit-markup-hw-03

body { background-color: var(--primary-white-color); color: var(--primary-text-color); font-family:
"Roboto", "Raleway", "Oleo Script", sans-serif; }

h1, h2, h3, h4, h5, h6, p, ul { padding: 0; margin: 0; }

img { display: block; max-width: 100%; height: auto; }

.list{ list-style: none;  
}

/_ колір основного тексту #212121 _/

/_ вторичний колір тексту #757575 _/

/_ колір тексту логотипу #FFFFFF _/

/_ чорний логотип хедер #000000 _/

/_ колір тексту #FFFFFF 60% _/

/_ акцент #2196F3 _/

/_ вторичний колір фона #F5F4FA _/

/_ колір фону героя та футера #2F303A _/

/_ колір фона хедера #ECECEC _/

:root { --primary-text-color: #212121; --secondary-text-color: #000; --title-text-color: #757575;
--footer-text-color:#FFFFFF60; --accent-color: #2196F3; --primary-white-color: #FFF;
--secondary-fon-color: #F5F4FA; --section-fon-color: #2F303A; --button-hover-color: #2196F350; }

.container { width: 1230px; padding-left: 15px; padding-right: 15px; margin-left: auto;
margin-right: auto; }

.section { padding: 94px 0; }

.main-nav { display: flex; align-items: center; justify-content: center; border-bottom: 1px solid
#ECECEC; } .logo { color: var(--secondary-text-color); font-family: 'Raleway'; font-weight: 700;
font-size: 26px; line-height: 1.19; text-decoration: none; letter-spacing: 0.03em; padding: 24px 0px
25px 0px; }

.logo-text { display: inline-block; color: var(--accent-color); }

/_ site-nav _/ .link { display: block; padding-top: 32px; padding-bottom: 32px;

    color:var(--primary-text-color);
    font-weight: 500;
    font-size: 14px;
    line-height: 1.14;
    text-decoration: none;
    letter-spacing: 0.02em;

}

.site-nav .link:hover , .site-nav .link:focus { color: var(--accent-color); } .site-nav { display:
flex; margin-left: 93px; } .site-nav .nav:not(:last-child) { margin-right: 50px; }

.site-nav .link.current { color: var(--accent-color);

}

.contacts { display: flex; margin-left: auto; }

.contacts .contact:not(:last-child) { margin-right: 50px; }

.link-contacts { display: block; padding-top: 32px; padding-bottom: 32px;

    color: var(--title-text-color);
    font-weight: 500;
    font-size: 14px;
    line-height: 1.14;
    text-decoration: none;
    letter-spacing: 0.02em;

} .contacts .link-contacts:hover, .contacts .link-contacts:focus { color: var(--accent-color);  
}

/_ hero _/ .hero { background-color: var(--section-fon-color); text-align: center; } .hero-title{
margin-bottom: 30px;

    color: var(--primary-white-color);
    font-weight: 900;
    font-size: 44px;
    line-height: 1.36;
    letter-spacing: 0.06em;
    text-transform: uppercase;

} .button { padding: 10px 32px; border-radius: 4px;

    color: var(--primary-white-color);
    background-color: var(--accent-color);
    font-family: inherit;
    font-weight: 700;
    font-size: 16px;
    line-height: 1.875;
    letter-spacing: 0.06em;
    cursor: pointer;

}

.button:hover,  
.button:focus { background-color: var(--button-hover-color); }

/_ section _/ .visually-hidden { position: absolute; white-space: nowrap; width: 1px; height: 1px;
overflow: hidden; border: 0; padding: 0; clip: rect(0 0 0 0); clip-path: inset(50%); margin: -1px; }
/_ features _/ .features-title { margin-bottom: 10px; font-family: 'Roboto'; font-weight: 700;
font-size: 14px; line-height: 1.14; letter-spacing: 0.03em; text-transform: uppercase; }

.section-features { display: flex; }

.section-features .features:not(:last-child) { margin-right: 30px; }

.text { color: var(--title-text-color); font-size: 14px; line-height: 1.7; letter-spacing: 0.03em; }

/_ work _/ .section-work { font-weight: 700; font-size: 36px; line-height: 1.166; text-align:
center; margin-bottom: 50px;  
}

.work { display: flex; }

.work .work-img:not(:last-child) { margin-right: 30px; }

/_ team _/ .section-team { background-color: var(--secondary-fon-color); letter-spacing: 0.03em;
text-align: center;

}

.team { font-weight: 700; font-size: 36px; line-height: 1.166; letter-spacing: 0.03em;
margin-bottom: 50px;

}

.items-team { display: flex; border: 1px; }

.items-team .team-image + .team-image { margin-left: 30px; }

.card { padding: 30px; }

.title { margin-bottom: 10px;

    font-weight: 500;
    font-size: 16px;
    line-height: 1.187;
    letter-spacing: 0.03em;

}

.subtitle { color: var(--title-text-color); font-size: 16px; line-height: 1.187; letter-spacing:
0.03em; }

.team-image { background-color: var(--primary-white-color); box-shadow: 0px 1px 3px rgba(0, 0, 0,
0.12), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 2px 1px rgba(0, 0, 0, 0.2); border-radius: 0px 0px 4px
4px;

    }

/_ footer _/ .footer { background-color: var(--section-fon-color); margin: 0; padding: 60px 0px; }

.logo-footer { color: var(--primary-white-color); font-family: 'Raleway'; font-weight: 700;
font-size: 26px; line-height: 1.192; text-decoration: none; letter-spacing: 0.03em; }

.logo-web { margin-bottom: 20px; color: var(--accent-color); display: inline-block; }

.link-adress { color: var(--primary-white-color); font-style: normal; font-size: 14px; line-height:
1.714; text-decoration: none; letter-spacing: 0.03em; margin-bottom: 9px; }

.link-items .link-name:not(:last-child) { margin-bottom: 9px; }

.link-items .link-adress:hover, .link-items .link-adress:focus { color: var(--accent-color); }

.link-item { color: var(--footer-text-color); font-style: normal; font-size: 14px; line-height:
1.714; text-decoration: none; letter-spacing: 0.03em; margin-bottom: 9px; }

.link-items .link-item:hover, .link-items .link-item:focus { color: var(--accent-color);}

/_ portfolio _/ .filter { display: flex; Justify-content: center; margin-bottom: 50px; }

.filter .filter-item:not(:last-child) { margin-right: 8px; }

.filter-button { cursor: pointer; background-color: var(--secondary-fon-color); font-family:
inherit; font-weight: 500; font-size: 16px; line-height: 1.625; letter-spacing: 0.03em; padding: 6px
22px; border-radius: 4px; border: 0; }

.filter .filter-button:hover, .filter .filter-button:focus { background-color: var(--accent-color);
} /_ products _/ .product-title { font-weight: 700; font-size: 18px; line-height: 2; letter-spacing:
0.06em; margin-bottom: 4px; }

.product { font-size: 16px; line-height: 1.875; letter-spacing: 0.03em; }

.products { display: flex; flex-wrap: wrap; }

.product-image { margin-right: 30px; margin-bottom: 30px;

}

.product-image:nth-child(3n) { margin-right: 0; }

.product-image:nth-last-child(-n+3) { margin-bottom: 0;

}

.box { padding: 20px 24px; border: 1px solid #EEE; border-top: 0;

}
