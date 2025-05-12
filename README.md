Create location - Создалл локацию, статус код - 200,
Body 'json'
{ 

"location": { 

"lat": -38.383494, 

"lng": 33.427362 

}, "accuracy": 50, 

"name": "Frontline house", 

"phone_number": "(+91) 983 893 3937", 

"address": "29, side layout, cohen 09", 

"types": [

 "shoe park", 

"shop"

 ],

 "website": "http://google.com", 

"language": "French-IN"

 }
_____________________________________________________________________________________

Get_location - в ответе сообщение уже после удаления данной локации, статус код - 404 Not Found,

place_id: f7ce36b1ee214d06ef6e4e7d9c67bbc4 // первоначальная локация

_____________________________________________________________________________________

Update_location - обновил локацию, статус код 200,

Body 'Json'

{ 

"place_id":"f7ce36b1ee214d06ef6e4e7d9c67bbc4", // обновляем адрес у старого ID

 "address":"100 Lenina street, RU", 

"key":"qaclick123" 

}

_____________________________________________
Delete_location - удалил обновленную локацию 
Body 'Json'

{ 
"place_id":"f7ce36b1ee214d06ef6e4e7d9c67bbc4" //  новая локация
}




