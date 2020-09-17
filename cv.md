## Resume
# Junior Front-End Developer

1. My name is **Aliaksandr Melnichuk**.

2. Contacts:

    * alejandro.mel420@gmail.com
    * +375 29 225 21 23
    * telegram: @un_sicario

3. I work hard and try to do everything to become a front-end developer. I'm good at solving problems.

4. Basic HTML, CSS (*BEM-methodology, Bootstrap and SCSS/SASS*), JS.

5.     
    ```javascript 
    function calcExchangeRate(currency1, currency2) {
    const api = `https://api.exchangeratesapi.io/latest?symbols=${currency1},${currency2}`;

    async function getCurrency() {

        const response = await fetch(api);

        const val = await response.json();

     return val;

     }
     getCurrency().then(val => {

        let res = val.rates[currency2] / val.rates[currency1];

        res = Math.round(res * 100) / 100;

        console.log(res);
     });
     }
       calcExchangeRate('USD', 'PLN'); 
       
        

6. 

7. I graduated from technical school and I have an incomplete higher education.

8. B1 (I studied in Poland and had some practice in communication with english-speaking people).
