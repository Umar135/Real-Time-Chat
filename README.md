## Add Dependencies

First, we need to install the necessary dependencies:

        composer require beyondcode/laravel-websockets

Next, we need to configure Laravel to use Pusher as its broadcast driver. Update the BROADCAST_DRIVER setting in the .env file to use pusher:

        BROADCAST_DRIVER=pusher

Then, configure the Pusher credentials in the .env file:

        PUSHER_APP_ID=your_app_id
        PUSHER_APP_KEY=your_app_key
        PUSHER_APP_SECRET=your_app_secret
        PUSHER_APP_CLUSTER=your_app_cluster
        
-> for pusher credentials create a pusher account.
