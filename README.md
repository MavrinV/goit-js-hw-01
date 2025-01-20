# goit-js-hw-01

function makeTransaction(quantity,pricePerDroid){
const totalPrice = quantit*pricePerDroid;
return `You ordered ${quantity} droids worth ${totalPrice} credits!`
}

function getShippingMessage(country,price,deliveryFee){
const totalPrice = deliveryFee+price;
return `You ordered ${country} droids worth ${totalPrice} credits!`
}

function getElementWidth(content,padding,border){
return parseFloat(content) + parseFloat(padding*2) +  parseFloat (border*2)
}
