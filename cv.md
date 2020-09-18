# 1. Sarvar Usmanov

## 2. Contacts

- Phone: +99890 996-67-85
- email: sarvar95yil@gmail.com
- telegram: https://t.me/bartsimpson
- VK: vk.com/sarvar_u

## 3. Summary

I work as a sales manager, I began to take an interest in and study the frontend half a year ago, I study the same amount, strengths - I learn quickly, logic is highly developed, as well as there were no problems with mathematics and algorithms, and I myself love all sorts of calculations ...

## 4. Skills

HTML, CSS, JS (basic knowledge) frameworks: jQuerry, and some of JS libraries.

## 5. Code examples

### JS
```JS
// changing element position (X and Y axis) on web page by keyboard arrow keys
const keys = {
    ArrowUp: false,
    ArrowDown: false,
    ArrowRight: false,
    ArrowLeft: false,
}

const setting = {
    start: false,
    score: 0,
    speed: 3,
    traffic: 3,
    x: 0,
    y: 0,
};

function playGame() {

    if (setting.start) {
        setting.score += setting.speed;
        score.innerHTML = "SCORE<br>" + setting.score;
        moveRoad();
        moveEnemy();
        if(keys.ArrowLeft && setting.x > 0) {
            setting.x -= setting.speed;
        }
        if(keys.ArrowRight && setting.x < gameArea.offsetWidth - car.offsetWidth) {
            setting.x += setting.speed;
        }
        if(keys.ArrowUp && setting.y > 0) {
            setting.y -= setting.speed;
        }
        if(keys.ArrowDown && setting.y < gameArea.offsetHeight - car.offsetHeight) {
            setting.y += setting.speed;
        }

        car.style.left = setting.x + 'px';
        car.style.top = setting.y + 'px';


        requestAnimationFrame(playGame);
    }
}
```

## 6. Experience

I have no work experience, I studied various video lessons, as well as GLO Academy marathons. There is a portfolio site where other work that I did together is indicated, with video tutorials. In addition, I study from the book "Learning JavaScript Programming (Head First JavaScript Programming: A Brain-Friendly Guide)"

## 7. Education

High graduated  (courses at the Micros training center (certificate available), online self-study).

## 8. English
I speak English at a higher than average level, my vocabulary is large, it is not difficult to find names for classes and variables, and my spoken language is also developed.

