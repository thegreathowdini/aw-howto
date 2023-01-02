# how to use anywheel

a repo of stuff we know about anywheel
- [the very basics](#basics)
- [ways to save money](#save)
- [what happens if...](#scenarios)
- [other tricks](#tricks)

<hr />
<a name="basics"/>

## the very basics
1. to get started, download either the [ios](https://apps.apple.com/sg/app/anywheel/id1453812982) or [android](https://play.google.com/store/apps/details?id=com.ytyiot.ebike.anywheel) app

2. before registering, check if you have an invite code (it gives you some benefit in the app). if you do, have it ready

3. to register, you need a phone number that can receive sms otp. register with that 

4. enter the invite code

5. you need credit to start a trip. to top up your credit, go to the profile menu (top left of home screen), click 'credits', then click 'top up'

6. to start a trip, click 'scan to ride' on the home screen, and scan the qr code on the bike. you need bluetooth and an internet connection

7. to end a trip, lock the bike while bluetooth on your phone is on. the app on your phone now shows a 10 min countdown timer

8. you have 10 mins to find a parking QR code and scan that using the app. scanning the code ends the trip

<hr />
<a name="save"/>

## ways to save money
0. by default, anywheel charges at \$1/30 mins or part thereof

1. while using the app, you can get coupons for various reasons at various values (using an invite code gets you a \$2 coupon). coupons offset trip fees and have these rules:
	- you can only use one coupon at a time. hence, a \$2 coupon covers a 1h trip, but 2x\$1 coupons do not
	- even with a coupon, you still need positive balance (or pass--see below) to start a trip. in particular, you can't start a trip if you have $0 credit and just a $2 coupon
	- to see your coupon, go to profile menu (top left of home screen), then 'credits', then 'my coupons'
	- there's no need to apply a coupon manually. on ending a trip, anywheel automatically applies the oldest coupon you have that can cover the trip's cost

2. you can also buy a pass. it's 6.9 for 7 days, 9.9 for 30 days, and 26.9 for 90 days. in the duration of a pass, the first 30 mins of any trip is free; after that, trips are charged at .5/30 mins. passes have these rules:
	- if you're on a pass, you don't need positive credit to start a trip, but you still need non-negative credit
	- pass can be stacked with coupons--your trip cost will be calculated at pass rate, and the value of at most one coupon you have can be used to offset that value	
	
3. every day, you can get points for doing various things
	- 5 pts for checking in
	- 5 pts for sharing a trip that started in the last 72h
	- 10 pts for a trip >5 mins, or >3 mins with the start and end locations not in the same area

4. points can be used to redeem passes and coupons: 
 	- 50 pts for $.5 coupon
 	- 300 pts for 1d pass
 	- 500 pts for 3d pass

hence, if you're patient and diligent, you can ride for free: create an account, check in everyday for 60 days, use the 300 pts to get a 1d pass<br>
at the home screen, the points stuff is at the mushroom-like thing in the top right corner

<hr />
<a name="scenarios"/>

## what happens if...
if you don't scan a parking QR code within 10 mins of locking the bike, you get a \$5 penalty

if you lock the bike but are nowhere near a parking QR code, you have the option to 'unlock to repark'. click that, scan the qr of the bike. the ride time continues. on locking the bike again, the 10 mins parking timer resets

if you cop a \$5 penalty, or have parked at a legit location but the app is not accepting it, you can appeal. in the appeal function you need photos showing the locked bike near a parking qr, and the bike serial number must be visible

if you buy/redeem a pass while you are on a pass, the validity of the current pass is extended by the time of the new pass. ie., passes stack

if your balance is negative, you cannot open bikes even if you are on pass or have coupons. from here you have 3 options: (1) top up credit, min $10; (2) if the balance went negative because of a parking penalty, reverse the penalty by successful appeal; (3) start a new account

trip charges are tabulated at the end of the trip. hence if a trip is started while on pass, and the pass expires during the trip, the first 30 mins of that trip are not free, and the trip is charged at $1/30 mins. conversely, if a pass is bought in the middle of a trip, the first 30 mins of that trip are free 

<hr />
<a name="tricks"/>

## tricks
we usually get a pass when using anywheel on long cycling trips, parking and restarting every half hour at parking locations. if we make no mistakes, this means our trip costs the same as the pass (which could be free)

scanning a QR code is not the only way to park--you can also manually enter the alphanumeric code of the parking location. you can find the code of the closest location by using 'find nearest parking area' when the parking timer comes up. if you are within 30m or so of the actual location (e.g., just across the road), the app allows you to park. this is useful on cycling trips because it means we don't have to detour too far off our intended path to reset the 30 min timer

you can redeem coupons with points while a trip is ongoing, and any coupons that exist at a trip's end are applicable to that trip (even if those coupons didn't exist at the trip's start). hence, it is adviable to keep 50 points on standby, and buy a coupon if a ride is found to exceed 30 mins

the trip time is only visible while the trip is ongoing or after the trip has ended--it is not visible after the bike is locked but the parking QR has yet to be scanned. hence, if you are unsure whether an ongoing ride has exceeded 30 mins, you should check the trip time, and buy a coupon if necessary, before locking the bike. if you have locked the bike and realised that you are unsure of the time, you should not proceed to scan the parking QR code; instead, you should 'unlock to repark' the bike to see the ride time and buy a coupon if necessary

scanning the QR code is not the only way to open a bike--you can also do it by entering the id of a bike, either the 10-digit one at the rear QR or the 'ANYxxxxx' one at the mudguard. this is useful when you want to reset without getting off the bike

points expire at the end of the calendar year, but pass vaidities can cross into new years. hence, cash out your points as passes near the end of the year

if you registered with a burner number, associate a facebook/gmail/apple account w your anywheel account to secure access

there's a way to get passes for points more cheaply. we won't disclose it publicly, but we'll share it with you if you ask

[not workable] obike had a race condition vulnerability we exploited to win one of their challenges (thrice). trying the exploit on anywheel gets you a 1 month suspension
