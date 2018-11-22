# php2FCM 

A PHP wrapper to send push notifications using Google's FCM (Firebase Cloud Messaging)

## Usage
    include('sendNotif.php');
    $push = new sendNotif();
    $push->set_api_key('API_KEY');
    $push->set_rid($rids); //Where $rid is an array of registration ids, atleast one is required
    $push->set_msg($title, $msg, $subtitle = null, $ticketText = null, $vibrate = true, $sound = 1);
    //You can also use a message array, check the code or FCM documention for the array format
    $push->set_msg_arr($array);

    $response = $push->send();
    
	
## Copyright

2016 - 2018 Peter Koech, [kipkoech.com](https://kipkoech.com/)

If you find it useful, let me know :wink:

You can contact me on [email](mailto:peter.koech@gmail.com).
# KEThesis-Hub

# php2FCM
