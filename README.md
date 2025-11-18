<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css"
        integrity="sha512-2SwdPD6INVrV/lHTZbO2nodKhrnDdJK9/kg2XD1r9uGqPo1cUbujc+IYdlYdEErWNu69gVcYgdxlmVmzTWnetw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>The-Thyroid-Specialist</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    * {
    margin: 0;
    padding: 0;
}

/* top-header */

.top-heade {
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(to right, #0076D0, #51AAEE);
}

.top-head {
    height: 42px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    max-width: 1465px;
    padding: 0 20px;
}

.top-sec {
    display: flex;
    align-items: center;
    gap: 10px;
}

.top-sec-child {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 5px;
    color: white;
    font-size: 12px;
    font-family: inter, sans-serif;
}

.top-sec-child p {
    font-size: 12px;
}

.top-sec-child i {
    font-size: 15px;
    color: black;
}


/* Header */

.header {
    display: flex;
    justify-content: center;
    align-items: center;
}

.navbar {
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    max-width: 1440px;
    padding: 0 20px;
}

.head-logo {
    font-family: Inter, sans-serif;
    font-weight: 700;
    font-style: Bold;
    line-height: 100%;
    color: rgba(0, 118, 208, 1);
}

nav {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    gap: 50px;
}

nav ul {
    display: flex;
    list-style: none;
    align-items: center;
    gap: 40px;
}

nav a {
    text-decoration-line: none;
    color: rgba(0, 0, 0, 1);
    font-family: inter, sans-serif;
    font-size: 16px;
    font-weight: 600;
    transition: color 0.2s ease;
}

nav ul li a:hover {
    color: #0076D0;
}

.btn button {
    background: linear-gradient(to right, #0076D0, #51AAEE);
    width: 174px;
    height: 36px;
    border-radius: 9px;
    color: white;
    border: none;
    cursor: pointer;
}

.btn button:hover {
    background: linear-gradient(to right, #0122a6, #51AAEE);
}

.hero {
    width: 100%;
    height: 555px;
    background: linear-gradient(to right, #0076D0, #51AAEE);
    display: flex;
    justify-content: center;
    align-items: center;
}

.herosection {
    display: flex;
    justify-content: center;
    width: 1770px;
}

.herro {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
}

.detail2 {
    display: flex;
    flex-direction: column;
    gap: 30px;
    padding: 10px 70px;
    text-align: center;
}

.detail2 h3 {
    font-family: Inter;
    font-weight: 700;
    font-size: 42px;
    line-height: 100%;
    text-align: center;
    color: white;
}

.aggarawal {
    font-family: Inter;
    font-weight: 600;
    font-style: Semi Bold;
    font-size: 22px;
    letter-spacing: 0%;
    text-align: center;
    background: radial-gradient(circle, #FFFFFF, #51AAEE, #0076D0);
    border: none;
}

.btn2 {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
}

.btn2 button {
    width: 206px;
    height: 36px;
    font-family: Inter;
    font-weight: 600;
    font-size: 16px;
    line-height: 100%;
    border-radius: 9px;
    border: none;
    color: white;
    cursor: pointer;
    background: linear-gradient(to right, #0076D0, #51AAEE);
}

.btn2 button:hover {
    background: linear-gradient(to right, #0122a6, #51AAEE);
}

.btn2 a {
    text-decoration-line: none;
    color: white;
}

.detail2 p {
    font-family: Inter;
    font-weight: 500;
    font-style: Medium;
    font-size: 18px;
    line-height: 100%;
    letter-spacing: 0%;
    text-align: center;
    color: white;
}

.detail1 {
    margin-top: 4px;
}

.detail3 {
    margin-top: 84px;
}

.services {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #EFFAFF85;
}

.special-service {
    text-align: center;
    width: 700px;
    padding: 90px 10px;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.special-service h1 {
    font-family: Inter;
    font-weight: 700;
    font-size: 39px;
    line-height: 100%;
    color: #0076D0;
}

.special-service p {
    font-family: Inter;
    font-weight: 500;
    font-size: 20px;
    line-height: 100%;
    text-align: center;
    color: #757575;
}

.thyroid-service {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #EFFAFF85;
}

.thyroid-syntum {
    max-width: 1400px;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 50px;
    padding: 40px;
}

.syntums {
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.2);
    border-bottom-left-radius: 26px;
    border-top-left-radius: 26px;
    border-top-right-radius: 26px;
    border-bottom-right-radius: 26px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.syntums:hover {
    transform: translateY(-20px);
    box-shadow: 0 3px 8px rgba(0, 0, 0, 0.3);
}

.deseace {
    padding: 30px 40px;
}

.deseace1 {
    background: linear-gradient(to right, #0076D0, #51AAEE);
    border-top-left-radius: 26px;
    border-top-right-radius: 26px;
}

.deseace1 img {
    padding-top: 25px;
    width: 100%;
    height: auto;
    display: block;
}

.deacesinfo {
    display: flex;
    flex-direction: column;
    gap: 30px;
}

.deacesinfo h2 {
    font-family: Inter;
    font-weight: 700;
    font-size: 24px;
    line-height: 100%;
    color: #0076D0;
}

.deacesinfo p {
    font-family: Inter;
    font-weight: 400;
    font-size: 16px;
    line-height: 20px;
    color: #9C9C9C;
}


.about-dr-aggarwal {
    display: flex;
    justify-content: center;
    align-items: center;
}

.about-box1 {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    justify-content: center;
    padding: 60px 0;
    gap: 20px;
}

.about-box1 h1 {
    font-family: Inter;
    font-weight: 700;
    font-size: 39px;
    line-height: 100%;
    color: #0076D0;
}

.about-box1 p {
    font-family: Inter;
    font-weight: 500;
    font-size: 20px;
    line-height: 100%;
    text-align: center;
    color: #757575;
}

.btn3 button {
    width: 169px;
    height: 23px;
    opacity: 1;
    border-radius: 11.5px;
    border-width: 1px;
    border: 1px solid #0076D0;
    background-color: #d0e8fa;
    color: black;
    font-family: Inter;
    font-weight: 600;
    font-size: 10px;
    line-height: 100%;
    text-align: center;
}

.health-sec {
    display: flex;
    justify-content: center;
    align-items: center;
}

.health-child {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 50px;
}

.health2 {
    display: flex;
    flex-direction: column;
    font-size: 20px;
    font-family: inter;
    color: #494949;
    width: 698px;
    gap: 40px;
}

.health2 h1 {
    color: #0076D0;
}

.dr-btn button {
    background: linear-gradient(to right, #0076D0, #51AAEE);
    color: white;
    border: none;
    border-radius: 40px;
    padding: 12px 30px;
    font-size: 16px;
    font-weight: 600;
    cursor: pointer;
    display: inline-flex;
    align-items: center;
    gap: 10px;
    transition: all 0.5s ease;
    box-shadow: 0 4px 10px rgba(0, 118, 208, 0.3);
}


.dr-btn button:hover {
    background: linear-gradient(to right, #0122a6, #51AAEE);
    box-shadow: 0 6px 15px rgba(0, 118, 208, 0.6);
    transform: translateY(-2px);
}

.dr-btn .arrow {
    transition: transform 0.5s ease;
}

.dr-btn:hover .arrow {
    transform: translateX(5px);
}



.thyroid-issu-sec {
    display: flex;
    justify-content: center;
    align-items: center;
}

.thyroidissu {
    display: flex;
    flex-direction: column;
    text-align: center;
    align-items: center;
    justify-content: center;
    width: 1322px;
    height: 408px;
    opacity: 1;
    gap: 40px;
    top: 2917px;
    left: 67px;
    border-radius: 36px;
    background: linear-gradient(to right, #0076D0, #51AAEE);
}

.thyroidissu h2 {
    font-family: Inter;
    font-weight: 700;
    font-size: 39px;
    line-height: 100%;
    color: white;
}

.thyroidissu p {
    font-family: Inter;
    font-weight: 400;
    font-size: 26px;
    line-height: 100%;
    text-align: center;
    color: #FFFFFF;
}

.btn4 {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 100px;
}

.btnn1 button {
    width: 264px;
    height: 40px;
    font-family: Inter;
    font-weight: 600;
    font-size: 16px;
    line-height: 100%;
    border-radius: 9px;
    border: none;
    color: white;
    cursor: pointer;
    background: linear-gradient(to right, #0076D0, #51AAEE);
    transition: background 8s ease;
}

.btnn2 button {
    background: transparent;
    width: 264px;
    height: 40px;
    border-radius: 9px;
    color: white;
    border: 1px solid white;
    font-family: Inter;
    font-weight: 600;
    font-size: 16px;
    line-height: 100%;
}

.treatment-sec {
    display: flex;
    justify-content: center;
    align-items: center;
}

.treatment {
    text-align: center;
    padding: 100px 0;
    margin-top: 70px;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.treatment h1 {
    font-family: Inter;
    font-weight: 700;
    font-size: 39px;
    line-height: 100%;
    color: #0076D0;
}

.treatment p {
    font-family: Inter;
    font-weight: 500;
    font-size: 20px;
    line-height: 100%;
    text-align: center;
    color: #757575;
}

.treatment-box {
    display: flex;
    justify-content: center;
    align-items: center;
}

.intreatment-box {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
}

.treat-box1 {
    background-color: #FBFBFB;
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.2);
    width: 284px;
    height: 289px;
    opacity: 1;
    border-radius: 18px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 50px 50px;
    gap: 30px;
    font-family: inter;
    margin-top: 185px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.treat-box1:hover {
    transform: translateY(-20px);
    box-shadow: 0 3px 8px rgba(0, 0, 0, 0.3);
}

.treat-box2 {
    background: linear-gradient(to right, #0076D0, #51AAEE);
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.2);
    width: 284px;
    height: 289px;
    opacity: 1;
    top: 3659px;
    left: 1040px;
    border-radius: 18px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 50px 50px;
    gap: 30px;
    font-family: inter;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.treat-box2:hover {
    transform: translateY(-20px);
    box-shadow: 0 3px 8px rgba(0, 0, 0, 0.3);
}

.treat-box {
    display: flex;
    align-items: center;
    gap: 10px;
}

.treat-box h2 {
    font-size: 30px;
    color: #51AAEE;
}

.treat-box h3 {
    font-size: 30px;
}

.treat-box p {
    font-family: Inter;
    font-weight: 500;
    font-style: Medium;
    font-size: 16px;
}

.treat-box button {
    width: 72px;
    height: 21px;
    opacity: 1;
    border-radius: 11.5px;
    border-width: 1px;
    border: 1px solid #0076D0;
    background-color: #d0e8fa;
    color: black;
    font-family: Inter;
    font-weight: 600;
    font-size: 10px;
    line-height: 100%;
    text-align: center;
}

.treat-box-arrow {
    display: flex;
    justify-content: flex-end;
    padding-right: 16px;
    font-size: 30px;
    color: #51AAEE;
}

.treat-boxx h1 {
    color: white;
    font-family: Inter;
    font-weight: 500;
    font-size: 24px;
}

.treat-boxx p {
    font-family: Inter;
    font-weight: 500;
    font-size: 16px;
    color: white;
}

.treat-boxx button {
    width: 72px;
    height: 21px;
    opacity: 1;
    border-radius: 11.5px;
    border-width: 1px;
    border: 1px solid #0076D0;
    background: #51AAEE;
    color: white;
    font-family: Inter;
    font-weight: 600;
    font-size: 10px;
    line-height: 100%;
    text-align: center;
}

.treat-box-arroww {
    display: flex;
    justify-content: flex-end;
    padding-right: 16px;
    font-size: 30px;
    color: white;
}

/* patient-story */

.patient-story {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 100px;
}

.patient {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 100px 0;
    gap: 40px;
}

.btn5 button {
    width: 169px;
    height: 23px;
    opacity: 1;
    border-radius: 11.5px;
    border-width: 1px;
    border: 1px solid #0076D0;
    background-color: #d0e8fa;
    color: black;
    font-family: Inter;
    font-weight: 600;
    font-size: 10px;
    line-height: 100%;
    text-align: center;
}

.story h1 {
    font-family: Inter;
    font-weight: 700;
    font-style: Bold;
    font-size: 39px;
    line-height: 100%;
    letter-spacing: 0%;
    color: #4C4C4C;
}

.story h2 {
    font-family: Inter;
    font-weight: 700;
    font-style: Bold;
    font-size: 39px;
    line-height: 100%;
    letter-spacing: 0%;
    color: #0076D0;
    margin-top: 5px;
}

.story p {
    font-family: Inter;
    font-weight: 500;
    font-style: Medium;
    font-size: 18px;
    line-height: 100%;
    letter-spacing: 0%;
    text-align: center;
    color: #757575;
}

/* review-section */

.review-sec {
    display: flex;
    justify-content: center;
    align-items: center;
}

.review-section {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 70px;
}

.review-box {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 197px;
    height: 103px;
    opacity: 1;
    top: 4446px;
    left: 207px;
    border-radius: 21px;
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.2);
    gap: 10px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.review-box:hover {
    transform: translateY(-20px);
    box-shadow: 0 3px 8px rgba(0, 0, 0, 0.3);
}

.review-box h1 {
    font-family: Inter;
    font-weight: 600;
    font-style: Semi Bold;
    font-size: 24px;
    line-height: 100%;
    letter-spacing: 0%;
    color: #0076D0;
}

.review-box p {
    font-family: Inter;
    font-weight: 500;
    font-style: Medium;
    font-size: 16px;
    line-height: 100%;
    letter-spacing: 0%;
    color: #454545;
}

.review-number {
    display: flex;
    justify-content: center;
    align-items: center;
    color: #0076D0;
}

.review-number h2:hover {
    transform: scale(0.9);
    cursor: pointer;
}

.condition-section {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 70px 0;
}

.condition {
    display: flex;
    align-items: center;
    width: 995px;
    height: 260px;
    opacity: 1;
    top: 4612px;
    left: 207px;
    border-radius: 14px;
    background: linear-gradient(to right, #0076D0, #51AAEE);
}

.condition2 {
    width: 700px;
    height: 250px;
    opacity: 1;
    padding: 0 35px;
    top: 4612px;
    left: 207px;
    border-bottom-left-radius: 14px;
    margin-top: 10px;
    background: linear-gradient(to bottom, #FFFFFF, #E4F3FC);
}

.condition3 {
    padding-top: 15px;
}

.sarah {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.sarah-head {
    display: flex;
    align-items: center;
    gap: 10px;
}


.sarah-rating input {
    display: none;
}

.sarah-rating p {
    font-family: Inter;
    font-weight: 600;
    font-style: Semi Bold;
    font-size: 18px;
    line-height: 100%;
    letter-spacing: 0%;
}

.sarah-rating label {
    color: #0076D0;
    cursor: pointer;
    transition: 0.3s;
}

.sarah-rating input:checked~label {
    color: #0076D0;
}

.sarah-head-right {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-family: Inter;
    font-weight: 700;
    font-style: Bold;
    font-size: 12px;
    line-height: 17px;
    letter-spacing: 0%;
    color: #454545;
}

.btn6 button {
    width: 169px;
    height: 23px;
    opacity: 1;
    border-radius: 11.5px;
    border-width: 1px;
    background-color: #d0e8fa;
    color: black;
    font-family: Inter;
    font-weight: 600;
    font-size: 10px;
    line-height: 100%;
    text-align: center;
}

.condition4 {
    display: flex;
    justify-content: center;
    align-items: center;
}

.para-box {
    display: flex;
    flex-direction: column;
    gap: 20px;
    width: 611px;
    height: 108px;
    opacity: 1;
    top: 4727px;
    left: 249px;
    padding-top: 20px;
}

.para-box a {
    font-size: 15px;
    font-family: inter;
    text-decoration-line: none;
    color: #454545;
}

.para-box p {
    font-family: inter;
    font-size: 15px;
    color: #454545;
}

.condition-sec-2 {
    width: 100%;
    height: 250px;
    margin-top: 10px;
    opacity: 1;
    top: 4649px;
    left: 883px;
    border-width: 1px;
    border-bottom-right-radius: 14px;
    background: linear-gradient(to bottom, #FFFFFF, #E4F3FC);
}

.h1 {
    display: flex;
    justify-content: center;
    font-family: Inter;
    font-weight: 700;
    font-size: 14px;
    line-height: 17px;
    padding-top: 35px;
    color: #0076D0;
}

.treat {
    display: flex;
    justify-content: space-between;
}

.treat1 {
    font-family: Inter;
    font-weight: 500;
    font-style: Medium;
    font-size: 14px;
    line-height: 100%;
    letter-spacing: 0%;
    color: #686868;
}

.treat-center {
    border-left: 1px solid black;
}

.treat1 button {
    width: 65px;
    height: 16px;
    opacity: 1;
    border-radius: 11.5px;
    border-width: 1px;
    background-color: #d0e8fa;
    color: black;
    font-family: Inter;
    font-weight: 600;
    font-size: 8px;
    line-height: 100%;
    text-align: center;
}

.condition-sec-child-2 {
    padding: 25px;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.sarah2 {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-bottom: 80px;
}

.condition-0-1 {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 45px;
}

.condition-0-2 {
    background: linear-gradient(to right, #0076D0, #51AAEE);
    width: 302px;
    height: 260px;
    opacity: 1;
    border-radius: 14px;
}

.condition-0-1-child {
    background: linear-gradient(to bottom, #FEF0FF, #FDD2FF);
    width: 302px;
    height: 244px;
    margin-top: 16px;
    opacity: 1;
    border-bottom-left-radius: 14px;
    border-bottom-right-radius: 14px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.condition-0-2-child {
    background: linear-gradient(to bottom, #FEFEFE, #ABFFD5);
    width: 302px;
    height: 244px;
    margin-top: 16px;
    opacity: 1;
    border-bottom-left-radius: 14px;
    border-bottom-right-radius: 14px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.condition-0-3-child {
    background: linear-gradient(to bottom, #F7F3FF, #C6AEFF);
    width: 302px;
    height: 244px;
    margin-top: 16px;
    border-bottom-left-radius: 14px;
    border-bottom-right-radius: 14px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.condition-bottom-box1 {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.condition-bottom-box2 {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 5px;
}

.condition-bottom-box2 p {
    font-family: Inter;
    font-weight: 400;
    font-size: 7px;
}

.condition-bottom-box1 a {
    font-family: Inter;
    font-weight: 400;
    font-size: 11px;
    text-decoration-line: none;
    color: #454545;
}

.condition-bottom-box {
    display: flex;
    justify-content: space-around;
    width: 247px;
    border-top: 1px solid black;
    padding-top: 14px;
    gap: 70px;
}

.sarah-2 {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px 20px;
    gap: 70px;
}

.condition-4 {
    padding: 10px 30px;
    padding-bottom: 40px;
}

.btn7 button {
    width: 75px;
    height: 15px;
    border-radius: 40px;
    border-width: 1px;
    font-family: Inter;
    font-weight: 400;
    font-size: 8px;
    border: 1px solid #8ECBF980;
}

.whatsapp-con {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 100px 0;
}

.colorword {
    color: #0076D0;
}

.whats-contact {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    gap: 30px;
}

.whats-contact h1,
.whats-contact span {
    font-family: Inter;
    font-weight: 700;
    font-style: Bold;
    font-size: 39px;
    line-height: 100%;
    letter-spacing: 0%;
    text-align: center;
}



.whats-contact p {
    font-family: Inter;
    font-weight: 500;
    font-style: Medium;
    font-size: 20px;
    line-height: 100%;
    letter-spacing: 0%;
    text-align: center;
    color: #757575;
}

.btn8 button {
    width: 102px;
    height: 21px;
    opacity: 1;
    border-radius: 11.5px;
    border-width: 1px;
    border: 1px solid #0076D0;
    background-color: #d0e8fa;
    color: black;
    font-family: Inter;
    font-weight: 600;
    font-size: 11px;
    line-height: 100%;
    text-align: center;
}

.btn8 i {
    color: #FB12C4;
}

.whatsapp-logo {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 250px;
    height: 72px;
    opacity: 1;
    top: 5597px;
    left: 573px;
    border-radius: 36px;
    gap: 10px;
    border-radius: 36px;
    background: linear-gradient(to bottom, #d0e8cc, #d1f9d1);
}

.whats p {
    font-family: Inter;
    font-weight: 500;
    font-style: Medium;
    font-size: 12px;
    line-height: 28px;
    letter-spacing: 0%;
}

.whats h1 {
    font-family: Inter;
    font-weight: 700;
    font-style: Bold;
    font-size: 23px;
    line-height: 28px;
    letter-spacing: 0%;
    color: #3EAF44;
}

.fill-detail {
    display: flex;
    justify-content: center;
    align-items: center;

}

.fill-details {
    display: flex;
    justify-content: center;
    align-items: center;
}

.form {
    width: 467px;
    height: 602px;
    opacity: 1;
    top: 5772px;
    left: 146px;
    border-radius: 24px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    background-color: #F6F6F6;
    padding: 64px;
}

.form h1 {
    font-family: inter;
    font-weight: 700;
    font-size: 35px;
    line-height: 21px;
    padding-bottom: 22px;
}

.contact-img {
    width: 883px;
    height: 590px;
    opacity: 1;
    top: 5779px;
    left: 718px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.contact-img img {
    width: 677px;
    height: 510px;
    opacity: 1;
    top: 5803px;
    left: 755px;

}

.putname input,
.putnumber input {
    width: 339px;
    height: 40px;
    opacity: 1;
    border-radius: 10px;
    border-width: 1px;
    padding: 0 15px;
    border: none;
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.2);
}

.you-are-new select {
    width: 371px;
    height: 43px;
    opacity: 1;
    border-radius: 10px;
    padding: 0 15px;
    font-family: inter;
    font-weight: 400;
    font-style: Regular;
    font-size: 12px;
    line-height: 28px;
    color: #8D8D8D;
    border: none;
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.2);
}

.set-perfect-date {
    display: flex;
    gap: 28px;
}

.set-perfect-date select {
    width: 171px;
    height: 44px;
    border-radius: 10px;
    border-width: 1px;
    opacity: 1;
    padding: 0 15px;
    font-family: inter;
    font-weight: 400;
    font-size: 12px;
    line-height: 28px;
    color: #8D8D8D;
    border: none;
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.2);
}

.add-massage textarea {
    width: 339px;
    height: 73px;
    opacity: 1;
    border-radius: 10px;
    border-width: 1px;
    padding: 22px 15px;
    font-family: inter;
    font-weight: 400;
    font-size: 16px;
    line-height: 28px;
    color: #8D8D8D;
    border: none;
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.2);
}

.i-agree {
    display: flex;
    align-items: center;
    gap: 10px;
}

.i-agree label {
    font-family: inter;
    font-weight: 400;
    font-size: 8px;
    line-height: 28px;
}

.btn9 button {
    width: 371px;
    height: 40px;
    top: 6294px;
    left: 204px;
    border-radius: 9px;
    opacity: 1;
    background: linear-gradient(to right, #0076D0, #51AAEE);
    font-family: Inter;
    font-weight: 600;
    font-size: 15px;
    line-height: 100%;
    color: white;
    border: none;
    border: none;
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.2);
    transition: 0.4s;
}

.btn9 button:hover {
    transform: scale(1.1);
    background: linear-gradient(to right, #0122a6, #51AAEE);
}

/* footer */

.footer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(to right, #0076D0, #51AAEE);
    width: 100%;
    height: 603px;

}

.foot {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 420px;
}

.foot1 {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.footchild {
    width: 529px;
    display: flex;
    flex-direction: column;
    gap: 35px;
}

.footicon {
    display: flex;
    align-items: center;
    gap: 15px;
}

.foot-icon {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 44px;
    height: 44px;
    background-color: #c2cdf45e;
    border-radius: 30px;
}

.footchild h1 {
    font-family: Inter;
    font-weight: 700;
    font-size: 29px;
    line-height: 100%;
    color: white;
}

.footchild p {
    font-family: Inter;
    font-weight: 400;
    font-size: 14px;
    line-height: 100%;
    color: white;
}

.btn10 button {
    width: 235px;
    height: 28px;
    border-radius: 40px;
    border-width: 1px;
    background-color: #8ECBF980;
    color: white;
    border: 1px solid rgb(232, 233, 248);
}

.foot-links {
    width: 229px;
    opacity: 1;
    display: flex;
    flex-direction: column;
    gap: 25px;
}

.foot-link {
    display: flex;
    flex-direction: column;
}

.foot-links a {
    font-family: Inter;
    font-weight: 400;
    font-size: 17px;
    line-height: 28px;
    color: white;
    text-decoration-line: none;
}



.footchild2 {
    display: flex;
    gap: 80px;
}

.footchild2 h1 {
    font-family: Inter;
    font-weight: 700;
    font-size: 29px;
    line-height: 100%;
    color: white;
}

.icon {
    display: flex;
    align-items: center;
    gap: 10px;
}

.icon2 {
    display: flex;
    align-items: baseline;
    gap: 19px;
}

.icon i {
    color: white;
}

.icon2 i {
    color: white;
}

.foot-link2 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 20px;
}


.timings {
    width: 1418px;
    opacity: 1;
    display: flex;
    justify-content: space-between;
    text-align: center;
    align-items: end;
    background-color: #e4e5fb5e;
    border-radius: 20px;
    padding: 14px 30px;
}

.time h1,
span {
    font-family: Inter;
    font-weight: 700;
    font-size: 16px;
    line-height: 100%;
    text-align: center;
    color: white;
}

.end-foot {
    width: 1566px;
    height: 0px;
    border-width: 1px;
    display: flex;
    justify-content: center;
    margin-top: 50px;
    border-top: 1px solid white;
}

.end-foot p {
    padding: 50px 0;
    color: white;
    font-family: Inter;
    font-weight: 400;
    font-size: 12px;
    line-height: 100%;
}

@media (max-width: 768px) {

    nav ul li   {
        display: none;
    }

    

    .thyroid-syntum {
        flex-wrap: wrap;
        display: flex;
    }


    .syntums {
        flex-wrap: wrap;
    }

    .health2 {
        flex-wrap: wrap;
        padding: 40px;
    }

    .thyroidissu {
        flex-wrap: wrap;
        display: flex;
        }

        .thyroid-issu-sec {
            flex-wrap: wrap;
        }

        .fill-detail {
            flex-wrap: wrap;
        }

    .detail1,
    .detail3 {
        display: none;
    }
    .health-child {
        display: flex;
        flex-direction: column;
    }

    .condition {
        flex-wrap: wrap;
    }

    .condition-0-1 {
        flex-wrap: wrap;
        margin-top: 250px;
    }
    .sarah2 {
        padding-bottom: 10px;
    }
    .intreatment-box {
        display: flex;
        flex-direction: column;
    }

    .review-section {
        flex-wrap: wrap;
    }

    .fill-details {
        flex-wrap: wrap;
    }

    .footer {
        width: 100%;
    }

    .foot {
        flex-wrap: wrap;
        display: flex;
        flex-direction: column;
        gap: 0px;
    }

    .working-time {
        display: none;
    }

    .end-foot {
        display: none;
    }
}
</style>

<body>

    <top-header class="top-heade">
        <div class="top-head">
            <div class="top-sec">
                <div class="top-sec-child">
                    <i class="fa-solid fa-phone"></i>
                    <p>(555) 123-4567</p>
                </div>
                <div class="top-sec-child">
                    <i class="fa-solid fa-location-dot"></i>
                    <p>123 Medical Center Drive, Suite 20</p>
                </div>
            </div>
            <div class="top-sec">
                <div class="top-sec-child">
                    <p>Mon-Fri: 8AM-5PM | Sat: 9AM-1PM</p>
                </div>
            </div>
        </div>
    </top-header>

    <header class="header">
        <div class="navbar">
            <div class="head-logo">
                <h1>The Thyroid Specialist</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="">Services</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>

                <div class="btn">
                    <button>Book Appointment</button>
                </div>

            </nav>

        </div>
    </header>

    <div class="hero">
        <div class="herosection">
            <div class="herro">
                <div class="detail1">
                    <img src="./images/heroimg1.png" alt="">

                </div>
                <div class="detail2">
                    <h3>Center for Thyroid, Breast, Diabetic Foot and Endocrine Oncosurgery</h3>
                    <div class="aggarawal">
                        <h5>Dr. Vivek Aggarwal</h5>
                    </div>
                    <p>Comprehensive endocrine and oncological surgical care with cutting-edge technology, personalized
                        treatment plans, and compassionate patient support.</p>
                    <div class="btn2">
                        <button>Schedule Consultation</button>
                        <a href="#">Learn More</a>
                    </div>
                </div>
                <div class="detail3">
                    <img src="./images/heroimg2.png" alt="">

                </div>
            </div>
        </div>
    </div>

    <div class="services">
        <div class="special-service">
            <h1>Our Specialized Services</h1>
            <p>Comprehensive thyroid care using the latest medical advances and personalized approaches</p>
        </div>
    </div>

    <div class="thyroid-service">
        <div class="thyroid-syntum">
            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg1.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Thyroid Disease</h2>
                        <p>The thyroid gland regulates metabolism, energy, and hormonal balance. Disorders like
                            hypothyroidism and hyperthyroidism can cause fatigue, weight changes, and mood swings.
                            Treatment
                            often involves medication, lifestyle changes, or surgery depending on severity</p>
                    </div>


                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg2.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Parathyroid</h2>
                        <p>Parathyroid glands control calcium levels in the blood and bones. Overactivity
                            (hyperparathyroidism) can lead to kidney stones, bone pain, and fatigue. Surgical removal of
                            the
                            affected gland is a common treatment when medication isn’t effective.</p>
                    </div>
                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg3.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Adrenal</h2>
                        <p>Adrenal glands produce hormones like cortisol and adrenaline. Disorders such as Addison’s
                            disease
                            or Cushing’s syndrome affect stress response, blood pressure, and metabolism. Diagnosis
                            often
                            involves hormone testing and imaging, with treatment ranging from medication to surgery.</p>
                    </div>
                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg4.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Laparoscopic Surgery</h2>
                        <p>Also known as minimally invasive surgery, this technique uses small incisions and a camera to
                            perform procedures. Benefits include reduced pain, quicker recovery, and minimal scarring.
                            It's
                            commonly used for gallbladder removal, hernia repair, and endocrine surgeries.</p>
                    </div>
                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg5.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Breast Cancer</h2>
                        <p>Breast cancer ranges from localized tumors to aggressive metastatic disease. Early detection
                            through mammograms and self-exams is key. Treatment may include surgery, chemotherapy,
                            radiation, and hormone therapy. A multidisciplinary approach improves outcomes</p>
                    </div>
                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg6.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Diabetic foot</h2>
                        <p>Diabetes can impair circulation and nerve function in the feet, increasing the risk of
                            ulcers,
                            infections, and slow healing. Preventive care—like regular foot checks, blood sugar control,
                            and
                            proper footwear—is essential to avoid serious complications</p>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <div class="about-dr-aggarwal">
        <div class="about-box1">
            <div class="btn3">
                <button>About Dr. Vivek Aggarwal</button>
            </div>
            <h1>Your Trusted Thyroid Specialist</h1>
            <p>With over 15 years of experience in endocrinology, Dr. Sarah Mitchell is dedicated to<br> providing
                comprehensive thyroid care with a focus on patient comfort and optimal <br> health outcomes.</p>
        </div>
    </div>

    <div class="health-sec">
        <div class="health-child">
            <div class="health">
                <img src="./images/dr.aggarwal.png" alt="">
            </div>
            <div class="health2">
                <h1>Dedicated to Your Thyroid Health</h1>
                <p>
                    The brain behind "CENTRE FOR THYROID, BREAST AND ENDOCRINE DISORDERS" is Dr. Vivek Aggarwal MS, MCh
                    (Endocrine Surg) who is the First Endocrine Surgeon of Delhi & International Surgical Foundation
                    Grant Awardee, Montreal, Canada.
                </p>
                <p>
                    He is a leading Endocrine specialist with years of rich experience behind him. His dream is to
                    provide complete Endocrine solutions to the society at a very nominal price. He has many rewards to
                    his credit and is an avid worker in the field of endocrine Surgery.
                </p>
                <div class="dr-btn">
                    <button>
                        Know Your Doctor
                        <span class="arrow">→</span>
                    </button>
                </div>
            </div>
        </div>
    </div>

    <div class="thyroid-issu-sec">
        <div class="thyroidissu">
            <h2>Ready to Take Control of Your Thyroid Health?</h2>
            <p>Don't let thyroid issues hold you back. Take the first step towards better health <br>with a
                comprehensive evaluation from our experienced team.</p>
            <div class="btn4">
                <div class="btnn1">
                    <button>Schedule Your Consultation</button>
                </div>
                <div class="btnn2">
                    <button>Learn More about Our services</button>
                </div>
            </div>
        </div>
    </div>

    <div class="treatment-sec">
        <div class="treatment">
            <h1>Your Treatment Journey</h1>
            <p>A clear, step-by-step approach to your thyroid health </p>
        </div>
    </div>

    <div class="treatment-box">
        <div class="intreatment-box">
            <div class="treatchild">
                <div class="treat-box1">
                    <div class="treat-box">
                        <h3>Initial</h3>
                        <h2>Consultation</h2>
                    </div>
                    <div class="treat-box">
                        <p>Comprehensive health <br>assessment and symptom <br>evaluation</p>
                    </div>
                    <div class="treat-box">
                        <button>60-Minuts</button>
                    </div>
                    <div class="treat-box-arrow">→</div>
                </div>
            </div>
            <div class="treat-box2">
                <div class="treat-boxx">
                    <h1>Diagnostic Testing</h1>
                </div>
                <div class="treat-boxx">
                    <p>Comprehensive health <br>assessment and symptom <br>evaluation</p>
                </div>
                <div class="treat-boxx">
                    <button>1-2 Days</button>
                </div>
                <div class="treat-box-arroww">→</div>
            </div>
            <div class="treat-box1">
                <div class="treat-box">
                    <h3>Treatment</h3>
                    <h2>planning</h2>
                </div>
                <div class="treat-box">
                    <p>Personalized treatment<br>plan development</p>
                </div>
                <div class="treat-box">
                    <button>30 Minuts</button>
                </div>
                <div class="treat-box-arrow">→</div>
            </div>
            <div class="treat-box2">
                <div class="treat-boxx">
                    <h1>Ongoing Care</h1>
                </div>
                <div class="treat-boxx">
                    <p>Regular monitoring and <br>treatment adjustments</p>
                </div>
                <div class="treat-boxx">
                    <button>Ongoing</button>
                </div>
                <div class="treat-boxx"></div>
            </div>
        </div>
    </div>

    <div class="patient-story">
        <div class="patient">
            <div class="story">
                <div class="btn5">
                    <button>100+ Five-Star Reviews</button>
                </div>
            </div>
            <div class="story">
                <h1>Life-Changing Results</h1>
                <h2>Real Patient Stories</h2>
            </div>
            <div class="story">
                <p>Discover how our personalized thyroid care has transformed the lives <br> of patients across Texas
                </p>
            </div>
        </div>
    </div>

    <div class="review-sec">
        <div class="review-section">
            <div class="review-box">
                <h1>500+</h1>
                <p>Happy Patients</p>
            </div>
            <div class="review-box">
                <div class="review-number">
                    <h1>4.9</h1>
                    <h2>★</h2>
                </div>
                <p>Star Avg Rating</p>
            </div>
            <div class="review-box">
                <h1>100%</h1>
                <p>Success Rate</p>
            </div>
            <div class="review-box">
                <h1>15+</h1>
                <p>Years Experience</p>
            </div>
        </div>
    </div>

    <div class="condition-section">
        <div class="condition">
            <div class="condition2">
                <div class="condition3">
                    <div class="sarah">
                        <div class="sarah-head">
                            <div class="sarah-logo">
                                <img src="./images/Ellipse 10.png" alt="">
                            </div>
                            <div class="sarah-rating">
                                <p>Sarah M.</p>
                                <input type="radio" name="star" id="star5">
                                <label for="star5">★</label>

                                <input type="radio" name="star" id="star4">
                                <label for="star4">★</label>

                                <input type="radio" name="star" id="star3">
                                <label for="star3">★</label>

                                <input type="radio" name="star" id="star2">
                                <label for="star2">★</label>

                                <input type="radio" name="star" id="star1">
                                <label for="star1">★</label>
                            </div>
                        </div>
                        <div class="sarah-head">
                            <div class="sarah-head-right">
                                <p>Condition</p>
                                <div class="btn6">
                                    <button>Hypothyroidism</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="condition4">
                    <div class="para-box">
                        <a href="#">"After years of struggling with thyroid issues,</a>
                        <p>I finally found relief under Dr. Vivek Aggarwal’s care. His
                            expertise and compassionate approach made all the difference. From diagnosis to treatment,
                            everything was
                            clearly explained and tailored to my needs. I feel healthier, more energetic, and truly
                            grateful for the support
                            I received at the Centre.</p>
                    </div>
                </div>
            </div>
            <div class="treat-center"></div>
            <div class="condition-sec-2">
                <div class="h1">
                    Treatment Journey
                </div>
                <div class="condition-sec-child-2">
                    <div class="treat">
                        <div class="treat1">
                            Initial Consultation
                        </div>
                        <div class="treat1">
                            <button>60 Minutes</button>
                        </div>
                    </div>
                    <div class="treat">
                        <div class="treat1">
                            Diagnostic Testing
                        </div>
                        <div class="treat1">
                            <button>2 Days</button>
                        </div>
                    </div>
                    <div class="treat">
                        <div class="treat1">
                            Treatment Planning
                        </div>
                        <div class="treat1">
                            <button>30 Minutes</button>
                        </div>
                    </div>
                    <div class="treat">
                        <div class="treat1">Ongoing Care</div>
                        <div class="treat1"><button>Ongoing</button></div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="sarah2">
        <div class="condition-0-1">
            <div class="condition-0-2">
                <div class="condition-0-1-child">
                    <div class="sarah-2">
                        <div class="sarah-head">
                            <div class="head-logo">
                                <img src="./images/Ellipse 10.png" alt="">
                            </div>
                            <div class="sarah-rating">
                                <p>Sarah M.</p>
                                <input type="radio" name="star" id="star5">
                                <label for="star5">★</label>

                                <input type="radio" name="star" id="star4">
                                <label for="star4">★</label>

                                <input type="radio" name="star" id="star3">
                                <label for="star3">★</label>

                                <input type="radio" name="star" id="star2">
                                <label for="star2">★</label>

                                <input type="radio" name="star" id="star1">
                                <label for="star1">★</label>
                            </div>
                        </div>

                        <div class="sarah-head">
                            <div class="sarah-head-right">
                                <img src="./images/Vector.png" alt="">
                            </div>
                        </div>
                    </div>

                    <div class="condition-4">
                        <p>"Dr. Thompson changed my life. After years of fatigue, I finally got the right diagnosis and
                            treatment."</p>
                    </div>

                    <div class="condition-bottom-box">
                        <div class="condition-bottom-box1">
                            <a href="#">Condition</a>
                            <a href="#">Treatment</a>
                        </div>
                        <div class="condition-bottom-box2">
                            <div class="btn7">
                                <button>Hypothyroidism</button>
                            </div>
                            <p>6 Months of Treatment</p>
                        </div>
                    </div>

                </div>
            </div>
            <div class="condition-0-2">
                <div class="condition-0-2-child">
                    <div class="sarah-2">
                        <div class="sarah-head">
                            <div class="head-logo">
                                <img src="./images/Ellipse 10.png" alt="">
                            </div>
                            <div class="sarah-rating">
                                <p>Sarah M.</p>
                                <input type="radio" name="star" id="star5">
                                <label for="star5">★</label>

                                <input type="radio" name="star" id="star4">
                                <label for="star4">★</label>

                                <input type="radio" name="star" id="star3">
                                <label for="star3">★</label>

                                <input type="radio" name="star" id="star2">
                                <label for="star2">★</label>

                                <input type="radio" name="star" id="star1">
                                <label for="star1">★</label>
                            </div>
                        </div>

                        <div class="sarah-head">
                            <div class="sarah-head-right">
                                <img src="./images/Vector.png" alt="">
                            </div>
                        </div>
                    </div>

                    <div class="condition-4">
                        <p>"Dr. Thompson changed my life. After years of fatigue, I finally got the right diagnosis and
                            treatment."</p>
                    </div>

                    <div class="condition-bottom-box">
                        <div class="condition-bottom-box1">
                            <a href="#">Condition</a>
                            <a href="#">Treatment</a>
                        </div>
                        <div class="condition-bottom-box2">
                            <div class="btn7">
                                <button>Hypothyroidism</button>
                            </div>
                            <p>6 Months of Treatment</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="condition-0-2">
                <div class="condition-0-3-child">
                    <div class="sarah-2">
                        <div class="sarah-head">
                            <div class="head-logo">
                                <img src="./images/Ellipse 10.png" alt="">
                            </div>
                            <div class="sarah-rating">
                                <p>Sarah M.</p>
                                <input type="radio" name="star" id="star5">
                                <label for="star5">★</label>

                                <input type="radio" name="star" id="star4">
                                <label for="star4">★</label>

                                <input type="radio" name="star" id="star3">
                                <label for="star3">★</label>

                                <input type="radio" name="star" id="star2">
                                <label for="star2">★</label>

                                <input type="radio" name="star" id="star1">
                                <label for="star1">★</label>
                            </div>
                        </div>

                        <div class="sarah-head">
                            <div class="sarah-head-right">
                                <img src="./images/Vector.png" alt="">
                            </div>
                        </div>
                    </div>

                    <div class="condition-4">
                        <p>"Dr. Thompson changed my life. After years of fatigue, I finally got the right diagnosis and
                            treatment."</p>
                    </div>

                    <div class="condition-bottom-box">
                        <div class="condition-bottom-box1">
                            <a href="#">Condition</a>
                            <a href="#">Treatment</a>
                        </div>
                        <div class="condition-bottom-box2">
                            <div class="btn7">
                                <button>Hypothyroidism</button>
                            </div>
                            <p>6 Months of Treatment</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="whatsapp-con">
        <div class="whats-contact">
            <div class="btn8">
                <button>
                    <i class="fa-solid fa-phone"></i>
                    Contact Us
                </button>
            </div>

            <h1>Schedule Your <span class="colorword">Consultation</span><br>Today</h1>
            <p>Take the first step towards optimal thyroid health. Our friendly team is <br>ready to help you schedule
                your appointment and answer any questions.</p>

            <div class="whatsapp-logo">
                <img src="./images/social-media_15789331 1.png" alt="">
                <div class="whats">
                    <p>Schedule your appointment</p>
                    <h1>on Whatsapp</h1>
                </div>
            </div>

        </div>
    </div>

    <div class="fill-detail">
        <div class="fill-details">
            <div class="form">
                <h1>Request an <span class="colorword"> Appointment</span></h1>
                <div class="putname">
                    <input type="text" name="name" id="name" placeholder="Your Name">
                </div>
                <div class="putnumber">
                    <input type="text" name="name" id="name" placeholder="Your Phone">
                </div>
                <div class="you-are-new">
                    <select name="name" id="value">
                        <option value="name">Are you a new patient</option>
                        <option value="name">YES</option>
                        <option value="name">NO</option>
                    </select>
                </div>

                <div class="you-are-new">
                    <select name="name" id="value">
                        <option value="name">Appointment Type</option>
                        <option value="name">YES</option>
                        <option value="name">NO</option>
                    </select>
                </div>

                <div class="set-perfect-date">
                    <select name="name" id="value">
                        <option value="name">Preferred Date</option>
                        <option value="name">YES</option>
                        <option value="name">NO</option>
                    </select>

                    <select name="name" id="value">
                        <option value="name">Preferred Time</option>
                        <option value="name">YES</option>
                        <option value="name">NO</option>
                    </select>
                </div>
                <div class="add-massage">
                    <textarea name="massage" id="massage" placeholder="Message or Questions"></textarea>
                </div>

                <div class="i-agree">
                    <input type="checkbox" name="agree" id="agree">
                    <label for="agree">I agree to be contacted by The thyroid specialist</label>
                </div>
                <div class="btn9">
                    <button>Submite</button>
                </div>
            </div>
            <div class="contact-img">
                <img src="./images/Mask group.png" alt="">
            </div>
        </div>
    </div>


    <div class="footer">
        <div class="foot">
            <div class="footchild">
                <div class="foot1">
                    <h1>The Thyroid Specialist</h1>
                    <div class="btn10">
                        <button>Thyroid & Endocrine Specialist</button>
                    </div>
                </div>
                <div class="foot1">
                    <p>Board-certified endocrinologist specializing in thyroid and hormone disorders. Providing
                        compassionate, evidence-based care with a focus on personalized treatment plans for over 15
                        years.</p>
                    <div class="footicon">
                        <div class="foot-icon">
                            <img src="./images/Layer 2.png" alt="">
                        </div>
                        <div class="foot-icon">
                            <img src="./images/Layer 2 (1).png" alt="">
                        </div>
                        <div class="foot-icon">
                            <img src="./images/Layer 2 (2).png" alt="">
                        </div>
                    </div>
                </div>
            </div>
            <div class="footchild2">
                <div class="foot-links">
                    <h1>Navigation</h1>
                    <div class="foot-link">
                        <a href="#">Home</a>
                        <a href="#">About</a>
                        <a href="#">Services</a>
                        <a href="#">Contact</a>
                        <a href="#">Book Appointment</a>
                    </div>
                </div>
                <div class="foot-links">
                    <h1>Get in Touch</h1>
                    <div class="foot-link2">
                        <div class="icon">
                            <i class="fa-solid fa-phone"></i>
                            <a href="#">9999349230</a>
                        </div>
                        </a>
                        <div class="icon">
                            <i class="fa-solid fa-envelope"></i>
                            <a href="#">dr.vivekaggarwal@yahoo.com</a>
                        </div>
                        <div class="icon2">
                            <i class="fa-solid fa-location-dot"></i>
                            <a href="#">65 A, Ekta Appartment
                                A2B Block, Paschim ViharNew Delhi - 110063</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="working-time">
            <div class="timings">
                <div class="time">
                    <h1>Monday - Friday <br> <span>8:00 AM - 5:00 PM</span></h1>
                </div>
                <div class="time">
                    <h1>Working Schedule</h1><br>
                    <h1>Saturday</h1><span>9:00 AM - 1:00 PM</span></h1>
                </div>
                <div class="time">
                    <h1>Sunday <br><span>closed</span></h1>

                </div>
            </div>
        </div>

        <div class="end-foot">
            <p>© 2025 The Thyroid Specialist. All rights reserved. | Dedicated to your thyroid health and wellbeing.</p>
        </div>

    </div>

</body>

</html>
</style>

<body>

    <top-header class="top-heade">
        <div class="top-head">
            <div class="top-sec">
                <div class="top-sec-child">
                    <i class="fa-solid fa-phone"></i>
                    <p>(555) 123-4567</p>
                </div>
                <div class="top-sec-child">
                    <i class="fa-solid fa-location-dot"></i>
                    <p>123 Medical Center Drive, Suite 20</p>
                </div>
            </div>
            <div class="top-sec">
                <div class="top-sec-child">
                    <p>Mon-Fri: 8AM-5PM | Sat: 9AM-1PM</p>
                </div>
            </div>
        </div>
    </top-header>

    <header class="header">
        <div class="navbar">
            <div class="head-logo">
                <h1>The Thyroid Specialist</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="">Services</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>

                <div class="btn">
                    <button>Book Appointment</button>
                </div>

            </nav>

        </div>
    </header>

    <div class="hero">
        <div class="herosection">
            <div class="herro">
                <div class="detail1">
                    <img src="./images/heroimg1.png" alt="">

                </div>
                <div class="detail2">
                    <h3>Center for Thyroid, Breast, Diabetic Foot and Endocrine Oncosurgery</h3>
                    <div class="aggarawal">
                        <h5>Dr. Vivek Aggarwal</h5>
                    </div>
                    <p>Comprehensive endocrine and oncological surgical care with cutting-edge technology, personalized
                        treatment plans, and compassionate patient support.</p>
                    <div class="btn2">
                        <button>Schedule Consultation</button>
                        <a href="#">Learn More</a>
                    </div>
                </div>
                <div class="detail3">
                    <img src="./images/heroimg2.png" alt="">

                </div>
            </div>
        </div>
    </div>

    <div class="services">
        <div class="special-service">
            <h1>Our Specialized Services</h1>
            <p>Comprehensive thyroid care using the latest medical advances and personalized approaches</p>
        </div>
    </div>

    <div class="thyroid-service">
        <div class="thyroid-syntum">
            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg1.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Thyroid Disease</h2>
                        <p>The thyroid gland regulates metabolism, energy, and hormonal balance. Disorders like
                            hypothyroidism and hyperthyroidism can cause fatigue, weight changes, and mood swings.
                            Treatment
                            often involves medication, lifestyle changes, or surgery depending on severity</p>
                    </div>


                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg2.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Parathyroid</h2>
                        <p>Parathyroid glands control calcium levels in the blood and bones. Overactivity
                            (hyperparathyroidism) can lead to kidney stones, bone pain, and fatigue. Surgical removal of
                            the
                            affected gland is a common treatment when medication isn’t effective.</p>
                    </div>
                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg3.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Adrenal</h2>
                        <p>Adrenal glands produce hormones like cortisol and adrenaline. Disorders such as Addison’s
                            disease
                            or Cushing’s syndrome affect stress response, blood pressure, and metabolism. Diagnosis
                            often
                            involves hormone testing and imaging, with treatment ranging from medication to surgery.</p>
                    </div>
                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg4.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Laparoscopic Surgery</h2>
                        <p>Also known as minimally invasive surgery, this technique uses small incisions and a camera to
                            perform procedures. Benefits include reduced pain, quicker recovery, and minimal scarring.
                            It's
                            commonly used for gallbladder removal, hernia repair, and endocrine surgeries.</p>
                    </div>
                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg5.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Breast Cancer</h2>
                        <p>Breast cancer ranges from localized tumors to aggressive metastatic disease. Early detection
                            through mammograms and self-exams is key. Treatment may include surgery, chemotherapy,
                            radiation, and hormone therapy. A multidisciplinary approach improves outcomes</p>
                    </div>
                </div>
            </div>

            <div class="syntums">
                <div class="deseace1">
                    <img src="./images/thyroidimg6.png" alt="">
                </div>
                <div class="deseace">
                    <div class="deacesinfo">
                        <h2>Diabetic foot</h2>
                        <p>Diabetes can impair circulation and nerve function in the feet, increasing the risk of
                            ulcers,
                            infections, and slow healing. Preventive care—like regular foot checks, blood sugar control,
                            and
                            proper footwear—is essential to avoid serious complications</p>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <div class="about-dr-aggarwal">
        <div class="about-box1">
            <div class="btn3">
                <button>About Dr. Vivek Aggarwal</button>
            </div>
            <h1>Your Trusted Thyroid Specialist</h1>
            <p>With over 15 years of experience in endocrinology, Dr. Sarah Mitchell is dedicated to<br> providing
                comprehensive thyroid care with a focus on patient comfort and optimal <br> health outcomes.</p>
        </div>
    </div>

    <div class="health-sec">
        <div class="health-child">
            <div class="health">
                <img src="./images/dr.aggarwal.png" alt="">
            </div>
            <div class="health2">
                <h1>Dedicated to Your Thyroid Health</h1>
                <p>
                    The brain behind "CENTRE FOR THYROID, BREAST AND ENDOCRINE DISORDERS" is Dr. Vivek Aggarwal MS, MCh
                    (Endocrine Surg) who is the First Endocrine Surgeon of Delhi & International Surgical Foundation
                    Grant Awardee, Montreal, Canada.
                </p>
                <p>
                    He is a leading Endocrine specialist with years of rich experience behind him. His dream is to
                    provide complete Endocrine solutions to the society at a very nominal price. He has many rewards to
                    his credit and is an avid worker in the field of endocrine Surgery.
                </p>
                <div class="dr-btn">
                    <button>
                        Know Your Doctor
                        <span class="arrow">→</span>
                    </button>
                </div>
            </div>
        </div>
    </div>

    <div class="thyroid-issu-sec">
        <div class="thyroidissu">
            <h2>Ready to Take Control of Your Thyroid Health?</h2>
            <p>Don't let thyroid issues hold you back. Take the first step towards better health <br>with a
                comprehensive evaluation from our experienced team.</p>
            <div class="btn4">
                <div class="btnn1">
                    <button>Schedule Your Consultation</button>
                </div>
                <div class="btnn2">
                    <button>Learn More about Our services</button>
                </div>
            </div>
        </div>
    </div>

    <div class="treatment-sec">
        <div class="treatment">
            <h1>Your Treatment Journey</h1>
            <p>A clear, step-by-step approach to your thyroid health </p>
        </div>
    </div>

    <div class="treatment-box">
        <div class="intreatment-box">
            <div class="treatchild">
                <div class="treat-box1">
                    <div class="treat-box">
                        <h3>Initial</h3>
                        <h2>Consultation</h2>
                    </div>
                    <div class="treat-box">
                        <p>Comprehensive health <br>assessment and symptom <br>evaluation</p>
                    </div>
                    <div class="treat-box">
                        <button>60-Minuts</button>
                    </div>
                    <div class="treat-box-arrow">→</div>
                </div>
            </div>
            <div class="treat-box2">
                <div class="treat-boxx">
                    <h1>Diagnostic Testing</h1>
                </div>
                <div class="treat-boxx">
                    <p>Comprehensive health <br>assessment and symptom <br>evaluation</p>
                </div>
                <div class="treat-boxx">
                    <button>1-2 Days</button>
                </div>
                <div class="treat-box-arroww">→</div>
            </div>
            <div class="treat-box1">
                <div class="treat-box">
                    <h3>Treatment</h3>
                    <h2>planning</h2>
                </div>
                <div class="treat-box">
                    <p>Personalized treatment<br>plan development</p>
                </div>
                <div class="treat-box">
                    <button>30 Minuts</button>
                </div>
                <div class="treat-box-arrow">→</div>
            </div>
            <div class="treat-box2">
                <div class="treat-boxx">
                    <h1>Ongoing Care</h1>
                </div>
                <div class="treat-boxx">
                    <p>Regular monitoring and <br>treatment adjustments</p>
                </div>
                <div class="treat-boxx">
                    <button>Ongoing</button>
                </div>
                <div class="treat-boxx"></div>
            </div>
        </div>
    </div>

    <div class="patient-story">
        <div class="patient">
            <div class="story">
                <div class="btn5">
                    <button>100+ Five-Star Reviews</button>
                </div>
            </div>
            <div class="story">
                <h1>Life-Changing Results</h1>
                <h2>Real Patient Stories</h2>
            </div>
            <div class="story">
                <p>Discover how our personalized thyroid care has transformed the lives <br> of patients across Texas
                </p>
            </div>
        </div>
    </div>

    <div class="review-sec">
        <div class="review-section">
            <div class="review-box">
                <h1>500+</h1>
                <p>Happy Patients</p>
            </div>
            <div class="review-box">
                <div class="review-number">
                    <h1>4.9</h1>
                    <h2>★</h2>
                </div>
                <p>Star Avg Rating</p>
            </div>
            <div class="review-box">
                <h1>100%</h1>
                <p>Success Rate</p>
            </div>
            <div class="review-box">
                <h1>15+</h1>
                <p>Years Experience</p>
            </div>
        </div>
    </div>

    <div class="condition-section">
        <div class="condition">
            <div class="condition2">
                <div class="condition3">
                    <div class="sarah">
                        <div class="sarah-head">
                            <div class="sarah-logo">
                                <img src="./images/Ellipse 10.png" alt="">
                            </div>
                            <div class="sarah-rating">
                                <p>Sarah M.</p>
                                <input type="radio" name="star" id="star5">
                                <label for="star5">★</label>

                                <input type="radio" name="star" id="star4">
                                <label for="star4">★</label>

                                <input type="radio" name="star" id="star3">
                                <label for="star3">★</label>

                                <input type="radio" name="star" id="star2">
                                <label for="star2">★</label>

                                <input type="radio" name="star" id="star1">
                                <label for="star1">★</label>
                            </div>
                        </div>
                        <div class="sarah-head">
                            <div class="sarah-head-right">
                                <p>Condition</p>
                                <div class="btn6">
                                    <button>Hypothyroidism</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="condition4">
                    <div class="para-box">
                        <a href="#">"After years of struggling with thyroid issues,</a>
                        <p>I finally found relief under Dr. Vivek Aggarwal’s care. His
                            expertise and compassionate approach made all the difference. From diagnosis to treatment,
                            everything was
                            clearly explained and tailored to my needs. I feel healthier, more energetic, and truly
                            grateful for the support
                            I received at the Centre.</p>
                    </div>
                </div>
            </div>
            <div class="treat-center"></div>
            <div class="condition-sec-2">
                <div class="h1">
                    Treatment Journey
                </div>
                <div class="condition-sec-child-2">
                    <div class="treat">
                        <div class="treat1">
                            Initial Consultation
                        </div>
                        <div class="treat1">
                            <button>60 Minutes</button>
                        </div>
                    </div>
                    <div class="treat">
                        <div class="treat1">
                            Diagnostic Testing
                        </div>
                        <div class="treat1">
                            <button>2 Days</button>
                        </div>
                    </div>
                    <div class="treat">
                        <div class="treat1">
                            Treatment Planning
                        </div>
                        <div class="treat1">
                            <button>30 Minutes</button>
                        </div>
                    </div>
                    <div class="treat">
                        <div class="treat1">Ongoing Care</div>
                        <div class="treat1"><button>Ongoing</button></div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="sarah2">
        <div class="condition-0-1">
            <div class="condition-0-2">
                <div class="condition-0-1-child">
                    <div class="sarah-2">
                        <div class="sarah-head">
                            <div class="head-logo">
                                <img src="./images/Ellipse 10.png" alt="">
                            </div>
                            <div class="sarah-rating">
                                <p>Sarah M.</p>
                                <input type="radio" name="star" id="star5">
                                <label for="star5">★</label>

                                <input type="radio" name="star" id="star4">
                                <label for="star4">★</label>

                                <input type="radio" name="star" id="star3">
                                <label for="star3">★</label>

                                <input type="radio" name="star" id="star2">
                                <label for="star2">★</label>

                                <input type="radio" name="star" id="star1">
                                <label for="star1">★</label>
                            </div>
                        </div>

                        <div class="sarah-head">
                            <div class="sarah-head-right">
                                <img src="./images/Vector.png" alt="">
                            </div>
                        </div>
                    </div>

                    <div class="condition-4">
                        <p>"Dr. Thompson changed my life. After years of fatigue, I finally got the right diagnosis and
                            treatment."</p>
                    </div>

                    <div class="condition-bottom-box">
                        <div class="condition-bottom-box1">
                            <a href="#">Condition</a>
                            <a href="#">Treatment</a>
                        </div>
                        <div class="condition-bottom-box2">
                            <div class="btn7">
                                <button>Hypothyroidism</button>
                            </div>
                            <p>6 Months of Treatment</p>
                        </div>
                    </div>

                </div>
            </div>
            <div class="condition-0-2">
                <div class="condition-0-2-child">
                    <div class="sarah-2">
                        <div class="sarah-head">
                            <div class="head-logo">
                                <img src="./images/Ellipse 10.png" alt="">
                            </div>
                            <div class="sarah-rating">
                                <p>Sarah M.</p>
                                <input type="radio" name="star" id="star5">
                                <label for="star5">★</label>

                                <input type="radio" name="star" id="star4">
                                <label for="star4">★</label>

                                <input type="radio" name="star" id="star3">
                                <label for="star3">★</label>

                                <input type="radio" name="star" id="star2">
                                <label for="star2">★</label>

                                <input type="radio" name="star" id="star1">
                                <label for="star1">★</label>
                            </div>
                        </div>

                        <div class="sarah-head">
                            <div class="sarah-head-right">
                                <img src="./images/Vector.png" alt="">
                            </div>
                        </div>
                    </div>

                    <div class="condition-4">
                        <p>"Dr. Thompson changed my life. After years of fatigue, I finally got the right diagnosis and
                            treatment."</p>
                    </div>

                    <div class="condition-bottom-box">
                        <div class="condition-bottom-box1">
                            <a href="#">Condition</a>
                            <a href="#">Treatment</a>
                        </div>
                        <div class="condition-bottom-box2">
                            <div class="btn7">
                                <button>Hypothyroidism</button>
                            </div>
                            <p>6 Months of Treatment</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="condition-0-2">
                <div class="condition-0-3-child">
                    <div class="sarah-2">
                        <div class="sarah-head">
                            <div class="head-logo">
                                <img src="./images/Ellipse 10.png" alt="">
                            </div>
                            <div class="sarah-rating">
                                <p>Sarah M.</p>
                                <input type="radio" name="star" id="star5">
                                <label for="star5">★</label>

                                <input type="radio" name="star" id="star4">
                                <label for="star4">★</label>

                                <input type="radio" name="star" id="star3">
                                <label for="star3">★</label>

                                <input type="radio" name="star" id="star2">
                                <label for="star2">★</label>

                                <input type="radio" name="star" id="star1">
                                <label for="star1">★</label>
                            </div>
                        </div>

                        <div class="sarah-head">
                            <div class="sarah-head-right">
                                <img src="./images/Vector.png" alt="">
                            </div>
                        </div>
                    </div>

                    <div class="condition-4">
                        <p>"Dr. Thompson changed my life. After years of fatigue, I finally got the right diagnosis and
                            treatment."</p>
                    </div>

                    <div class="condition-bottom-box">
                        <div class="condition-bottom-box1">
                            <a href="#">Condition</a>
                            <a href="#">Treatment</a>
                        </div>
                        <div class="condition-bottom-box2">
                            <div class="btn7">
                                <button>Hypothyroidism</button>
                            </div>
                            <p>6 Months of Treatment</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="whatsapp-con">
        <div class="whats-contact">
            <div class="btn8">
                <button>
                    <i class="fa-solid fa-phone"></i>
                    Contact Us
                </button>
            </div>

            <h1>Schedule Your <span class="colorword">Consultation</span><br>Today</h1>
            <p>Take the first step towards optimal thyroid health. Our friendly team is <br>ready to help you schedule
                your appointment and answer any questions.</p>

            <div class="whatsapp-logo">
                <img src="./images/social-media_15789331 1.png" alt="">
                <div class="whats">
                    <p>Schedule your appointment</p>
                    <h1>on Whatsapp</h1>
                </div>
            </div>

        </div>
    </div>

    <div class="fill-detail">
        <div class="fill-details">
            <div class="form">
                <h1>Request an <span class="colorword"> Appointment</span></h1>
                <div class="putname">
                    <input type="text" name="name" id="name" placeholder="Your Name">
                </div>
                <div class="putnumber">
                    <input type="text" name="name" id="name" placeholder="Your Phone">
                </div>
                <div class="you-are-new">
                    <select name="name" id="value">
                        <option value="name">Are you a new patient</option>
                        <option value="name">YES</option>
                        <option value="name">NO</option>
                    </select>
                </div>

                <div class="you-are-new">
                    <select name="name" id="value">
                        <option value="name">Appointment Type</option>
                        <option value="name">YES</option>
                        <option value="name">NO</option>
                    </select>
                </div>

                <div class="set-perfect-date">
                    <select name="name" id="value">
                        <option value="name">Preferred Date</option>
                        <option value="name">YES</option>
                        <option value="name">NO</option>
                    </select>

                    <select name="name" id="value">
                        <option value="name">Preferred Time</option>
                        <option value="name">YES</option>
                        <option value="name">NO</option>
                    </select>
                </div>
                <div class="add-massage">
                    <textarea name="massage" id="massage" placeholder="Message or Questions"></textarea>
                </div>

                <div class="i-agree">
                    <input type="checkbox" name="agree" id="agree">
                    <label for="agree">I agree to be contacted by The thyroid specialist</label>
                </div>
                <div class="btn9">
                    <button>Submite</button>
                </div>
            </div>
            <div class="contact-img">
                <img src="./images/Mask group.png" alt="">
            </div>
        </div>
    </div>


    <div class="footer">
        <div class="foot">
            <div class="footchild">
                <div class="foot1">
                    <h1>The Thyroid Specialist</h1>
                    <div class="btn10">
                        <button>Thyroid & Endocrine Specialist</button>
                    </div>
                </div>
                <div class="foot1">
                    <p>Board-certified endocrinologist specializing in thyroid and hormone disorders. Providing
                        compassionate, evidence-based care with a focus on personalized treatment plans for over 15
                        years.</p>
                    <div class="footicon">
                        <div class="foot-icon">
                            <img src="./images/Layer 2.png" alt="">
                        </div>
                        <div class="foot-icon">
                            <img src="./images/Layer 2 (1).png" alt="">
                        </div>
                        <div class="foot-icon">
                            <img src="./images/Layer 2 (2).png" alt="">
                        </div>
                    </div>
                </div>
            </div>
            <div class="footchild2">
                <div class="foot-links">
                    <h1>Navigation</h1>
                    <div class="foot-link">
                        <a href="#">Home</a>
                        <a href="#">About</a>
                        <a href="#">Services</a>
                        <a href="#">Contact</a>
                        <a href="#">Book Appointment</a>
                    </div>
                </div>
                <div class="foot-links">
                    <h1>Get in Touch</h1>
                    <div class="foot-link2">
                        <div class="icon">
                            <i class="fa-solid fa-phone"></i>
                            <a href="#">9999349230</a>
                        </div>
                        </a>
                        <div class="icon">
                            <i class="fa-solid fa-envelope"></i>
                            <a href="#">dr.vivekaggarwal@yahoo.com</a>
                        </div>
                        <div class="icon2">
                            <i class="fa-solid fa-location-dot"></i>
                            <a href="#">65 A, Ekta Appartment
                                A2B Block, Paschim ViharNew Delhi - 110063</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="working-time">
            <div class="timings">
                <div class="time">
                    <h1>Monday - Friday <br> <span>8:00 AM - 5:00 PM</span></h1>
                </div>
                <div class="time">
                    <h1>Working Schedule</h1><br>
                    <h1>Saturday</h1><span>9:00 AM - 1:00 PM</span></h1>
                </div>
                <div class="time">
                    <h1>Sunday <br><span>closed</span></h1>

                </div>
            </div>
        </div>

        <div class="end-foot">
            <p>© 2025 The Thyroid Specialist. All rights reserved. | Dedicated to your thyroid health and wellbeing.</p>
        </div>

    </div>

</body>

</html>
