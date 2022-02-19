Hi,

To display a notification you should call it like below:

# Client side

exports['zaphNotify']:Alert("Title", "Message", Time, 'type')

# Server side

TriggerClientEvent('zaphNotify:Alert', source, "Title", "Message", Time, 'type')


[Time] - 1000 = 1 second | 5000 = 5 seconds

come to my developer server : https://discord.gg/YvvPAQ5Dt5
