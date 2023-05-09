Coin counter

* make a function takes PRICE x.xx
      4.99 price
 * quarter = .25
  * dime = .10
  * nickle = .05
  * penny = .01

coins= {
    
    [quarter: 19],
    [dimes : 2],
    [nickles: 0],
    [pennies: 4],

    }

  
  function howManyQuarters(price){
    let quarterCounter= 0;
    if (price - .25 >= .25){
        quarterCounter +=1;
        return howManyQuarters(price - .25);
    }
    //push quarterCounter to array in key value pair;
    return price;
  }
  // quarters = {quarters:19, leftOverPrice: .24 }
    dimes = {dimes:2, leftOverPrice: .04}

    coins: {quarters: 19, dimes: 2, nickles: 0 , pennies: 4}

  function howManyPennies(leftOverPrice{
    
  })


  5.99
  599
  const quarters = math.floor(599/25)
  leftOverPrice =  totalprice-quarters