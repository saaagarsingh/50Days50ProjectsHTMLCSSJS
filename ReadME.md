font-awesome cdn link :  "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" 

Roboto Font import link: @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');


basic CSS applied to every Project:
Note: this styling might change based on the requirement

*{
    box-sizing: border-box;
}

body{
    font-family: 'Roboto', 'sans-serif';
    margin: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    height: 100vh;
}