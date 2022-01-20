<p align="center">
     <h1 align='center'>FlickyTricky</h1>
</p>
<br>
<p align='center'>
    <p align='center'>🕊️ FlickyTricky is an Modern Android 2D Shooting Game, which enables the user to move and shoot using Eye Guestor with Auto Pause and Resume when the user Face is Not Found </p>
 </p>
 <br>
<p align="center">
  <img width="750" src="https://user-images.githubusercontent.com/81013192/150317119-b003293e-f6ac-4549-bcd6-078178cd54db.jpg" alt="FlickyTrickt logo">
</p>
<br>

## TechStack
- Minimum SDK 21
- [Google Play Service Vision](https://developers.google.com/android/reference/com/google/android/gms/vision/package-summary) is used to detect Eye Blink Detection
- [Google Game Activity](https://developer.android.com/games/agdk/integrate-game-activity) is used to control the game movement's by the result from Vision Service

## Architecture
### GameActivity 
<p align='center'>
   <img src="https://user-images.githubusercontent.com/81013192/150321008-bd4ced51-696a-4ba1-905f-2b7d668d18b2.png" alt="GameActivity Cycle">
</p>

### PlayService
<p align='center'>
  <img width="600" src='https://user-images.githubusercontent.com/81013192/150322473-f69c21e5-e306-44fb-9e47-67f9df8bc3f6.jpg'>
</p>

## Direction To Use

1. Open your eye's to move up
2. blink to shoot or Close your eye's to move down and shoot (More precisely this take's the movement of the eye lid)
3. When user face not found Game Automatically Pause's
4. When user face found again Game Automatically Resume's

## License

