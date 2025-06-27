<h1 tabindex="-1" class="heading-element" dir="auto">Frontend-разработка</h1>

**Сайт до:**
	
![](https://github.com/user-attachments/assets/447c4c23-333a-4eef-9326-338523456caf)
**Сайт после:**

![](https://github.com/user-attachments/assets/deed0e24-54dc-4a4f-a2b8-d595f3988f9c)

**Код:**
```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="utf-8">
	<title>Skillbox — сайт находится в разработке</title>
	<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
	<style>
	html, body {
		height: 100%;
		font-family: Roboto;
	}
	h2 {
		color: green;
	}
	h3 {
		color: #f0693c;
	}
	body {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	</style>
	<script>
	// Set the date we're counting down to
	var countDownDate = new Date("Jun 5, 2025 00:40:25").getTime();

	// Update the count down every 1 second
	var x = setInterval(function() {

	  // Get today's date and time
	  var now = new Date().getTime();

	  // Find the distance between now and the count down date
	  var distance = countDownDate - now;

	  // Time calculations for days, hours, minutes and seconds
	  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
	  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
	  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
	  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

	  // Display the result in the element with id="demo"
	  document.getElementById("countdown").innerHTML = days + " дн. " +
		hours + " ч " +
		minutes + " мин " +
		seconds + " с";

	  // If the count down is finished, write some text
	  if (distance < 0) {
	    clearInterval(x);
	    document.getElementById("countdown").innerHTML = "ПРЯМО СЕЙЧАС";
	  }
	}, 1000);
	</script>
</head>
<body>
	<h1>Skillbox</h1>
	<h2>Моё прохождение курса начнётся через: <span id="countdown"></span></h2>
	<h3>Вы можете связаться с нами:</h3>
	<div>Телефон: +7 (495) 154-09-36</div>
	<div>Email: hello@skillbox.ru</div>
	<div>Instagram: <a href="https://www.instagram.com/skillbox.ru" target="_blank">@skillbox.ru</a></div>
	<div>Youtube: <a href="https://www.youtube.com/channel/UCHJZFCpwlXV7Sie1dV6pQLw" target="_blank">@skillboxprogramming</a></div>
</body>
</html>
```
<h1 tabindex="-1" class="heading-element" dir="auto">Разработка на Java</h1>

**Задача 1**

![](https://github.com/user-attachments/assets/d01c8c07-e3c7-484b-8806-3ea33eb5ab1a)

**Код:**
```html
 System.out.println("Система расчёта штрафов");
    
    int carSpeed = 78;
    
    int fineFor1to10 = 30;
    int fineFor11to15 = 50;
    int fineFor16to20 = 70;
    int fineFor21to25 = 115;
    int fineFor26to30 = 180;
    int fineFor31to40 = 260;
    int fineFor41to50 = 400;
    int fineFor51to60 = 560;
    int fineFor61to70 = 700;
    int fineFor70andMore = 800;
    
    int townSpeed = 50;
    
    int overSpeed = carSpeed - townSpeed;
    
    if(overSpeed < 1) {
      System.out.println("Скорость не превышена или превышена незначительно");
    }

    else if(overSpeed >= 1 && overSpeed <= 10) {
        System.out.println("Штраф: " + fineFor1to10);}
        
    else if(overSpeed >= 11 && overSpeed <= 15) {
        System.out.println("Штраф: " + fineFor11to15);}
        
    else if(overSpeed >= 16 && overSpeed <= 20) {
        System.out.println("Штраф: " + fineFor16to20);}
        
    else if(overSpeed >= 21 && overSpeed <= 25) {
        System.out.println("Штраф: " + fineFor21to25);}
        
    else if(overSpeed >= 26 && overSpeed <= 30) {
        System.out.println("Штраф: " + fineFor26to30);}
    
    else if(overSpeed >= 31 && overSpeed <= 40) {
        System.out.println("Штраф: " + fineFor31to40);}
        
    else if(overSpeed >= 41 && overSpeed <= 50) {
        System.out.println("Штраф: " + fineFor41to50);}
        
    else if(overSpeed >= 51 && overSpeed <= 60) {
        System.out.println("Штраф: " + fineFor51to60);}
    
    else if(overSpeed >= 61 && overSpeed <= 70) {
        System.out.println("Штраф: " + fineFor61to70);}
        
    else if(overSpeed >= 70) {
        System.out.println("Штраф: " + fineFor70andMore);}
```

**Задача 2**

![](https://github.com/user-attachments/assets/a5446256-9b3e-4f07-84dd-47a4ec0987ce)

**Код:**
```html
System.out.println("Система расчёта штрафов в Германии");
    
    int carSpeed = 78;
    
    int fineFor1to10 = 30;
    int fineFor11to15 = 50;
    int fineFor16to20 = 70;
    int fineFor21to25 = 115;
    int fineFor26to30 = 180;
    int fineFor31to40 = 260;
    int fineFor41to50 = 400;
    int fineFor51to60 = 560;
    int fineFor61to70 = 700;
    int fineFor70andMore = 800;
    
    int townSpeed = 50;
    
    int overSpeed = carSpeed - townSpeed;
    
    if(overSpeed < 1) {
      System.out.println("Скорость не превышена или превышена незначительно");
    }

    else if(overSpeed >= 1 && overSpeed <= 10) {
        System.out.println("Штраф: " + fineFor1to10 + " евро.");}
        
    else if(overSpeed >= 11 && overSpeed <= 15) {
        System.out.println("Штраф: " + fineFor11to15 + " евро.");}
        
    else if(overSpeed >= 16 && overSpeed <= 20) {
        System.out.println("Штраф: " + fineFor16to20 +  "евро.");}
        
    else if(overSpeed >= 21 && overSpeed <= 25) {
        System.out.println("Штраф: " + fineFor21to25 + " евро.");}
        
    else if(overSpeed >= 26 && overSpeed <= 30) {
        System.out.println("Штраф: " + fineFor26to30 + " евро.");}
    
    else if(overSpeed >= 31 && overSpeed <= 40) {
        System.out.println("Штраф: " + fineFor31to40 + " евро.");}
        
    else if(overSpeed >= 41 && overSpeed <= 50) {
        System.out.println("Штраф: " + fineFor41to50 + " евро.");}
        
    else if(overSpeed >= 51 && overSpeed <= 60) {
        System.out.println("Штраф: " + fineFor51to60 + " евро.");}
    
    else if(overSpeed >= 61 && overSpeed <= 70) {
        System.out.println("Штраф: " + fineFor61to70 + " евро.");}
        
    else if(overSpeed >= 70) {
        System.out.println("Штраф: " + fineFor70andMore + " евро.");}
```

**Задача 3**
**Код:**
```html
```

**Задача 4**

![](https://github.com/user-attachments/assets/faf9e2af-c8d4-4a1e-888a-1579203e616f)
![](https://github.com/user-attachments/assets/84100d31-edba-4f4c-aa46-828f5143e84a)
![](https://github.com/user-attachments/assets/62b01ca3-f8b7-4b10-92f5-8d6314e941b5)
![](https://github.com/user-attachments/assets/867a5e9e-1dfa-46ea-ab4f-97393d35d79b)


**Код:**
```html
System.out.println("Система расчёта штрафов");
    
    int carSpeed = 87;
    boolean isTown = true;
    int countrySpeed = 90;
    
    int fineFor20to40 = 500;
    int fineFor40to60 = 1000;
    int fineFor60to80 = 2000;
    int fineFor80andMore = 5000;
    
    int townSpeed = 60;
    
    int overSpeed;
    if(isTown) {
        overSpeed = carSpeed - townSpeed;}
        else {
            overSpeed = carSpeed - countrySpeed;}
    
    if(overSpeed < 20) {
      System.out.println("Скорость не превышена или превышена незначительно");}
      
    else if(overSpeed >= 20 && overSpeed < 40) {
      System.out.println("Штраф: " + fineFor20to40);}
      
    else if(overSpeed >= 40 && overSpeed < 60) {
      System.out.println("Штраф: " + fineFor40to60);}
      
    else if(overSpeed >= 60 && overSpeed < 80) {
      System.out.println("Штраф: " + fineFor60to80);}
      
    else if(overSpeed >= 80) {
      System.out.println("Штраф: " + fineFor80andMore);}
```
<h1 tabindex="-1" class="heading-element" dir="auto">Разработка на Python</h1>

**Код после всех заданий:**

```html
print("Система расчёта штрафов")

car_speed = 111
is_town = True
is_camera = True

fine_for_1_to_10 = 30
fine_for_11_to_15 = 50
fine_for_16_to_20 = 70
fine_for_21_to_25 = 115
fine_for_26_to_30 = 180
fine_for_31_to_40 = 260
fine_for_41_to_50 = 400
fine_for_51_to_60 = 560
fine_for_61_to_70 = 700
fine_for_over_70 = 800

town_speed = 50
country_speed = 70

if is_town:
    over_speed = car_speed - town_speed
else:
    over_speed = car_speed - country_speed

if over_speed < 1:
    print("Скорость не превышена")
elif over_speed >= 1 and over_speed <= 10:
    print("Штраф: " + str(fine_for_1_to_10) + " евро")
elif over_speed >= 11 and over_speed <= 15:
    print("Штраф: " + str(fine_for_11_to_15) + " евро")
elif over_speed >= 16 and over_speed <= 20:
    print("Штраф: " + str(fine_for_16_to_20) + " евро")
elif over_speed >= 21 and over_speed <= 25:
    print("Штраф: " + str(fine_for_21_to_25) + " евро")
elif over_speed >= 26 and over_speed <= 30:
    print("Штраф: " + str(fine_for_26_to_30) + " евро")
elif over_speed >= 31 and over_speed <= 40:
    print("Штраф: " + str(fine_for_31_to_40) + " евро")
elif over_speed >= 41 and over_speed <= 50:
    print("Штраф: " + str(fine_for_41_to_50) + " евро")
elif over_speed >= 51 and over_speed <= 60:
    print("Штраф: " + str(fine_for_51_to_60) + " евро")
elif over_speed >= 61 and over_speed <= 70:
    print("Штраф: " + str(fine_for_61_to_70) + " евро")
    if is_camera and over_speed >= 60:
        print("Лишение водительских прав на 1 месяц")
elif over_speed > 70:
    print("Штраф: " + str(fine_for_over_70) + " евро")
    if is_camera:
        print("Лишение водительских прав на 3 месяца")

if over_speed >= 60:
    print("Внимание! Превышение скорости на 60 км/ч или более!")
    if not is_camera:
        print("Возможно лишение прав по решению суда")
```
**Результат:**

![](https://github.com/user-attachments/assets/e33c4416-3450-416b-9d8f-4ba246d1ef90)
<h1 tabindex="-1" class="heading-element" dir="auto">Тестирование (QA)</h1>

**Задача 1**

**Задача 2**

![](https://github.com/user-attachments/assets/afac146f-8e67-4b69-815b-81cfeaa87a39)

```html
public class Main
{
	public static void main (String[] args) {
		System.out.println("Система расчёта штрафов");
		
		check(-20, 0);
		check(0, 0);
		check(25, 0);
		check(50, 0);
		check(51, 15);
		check(55, 15);
		check(60, 15);
		check(61, 25);
		check(63, 25);
		check(65, 25);
		check(66, 35);
		check(68, 35);
		check(70, 35);
		check(71, 80);
		check(73, 80);
		check(75, 80);
		check(76, 100);
		check(78, 100);
		check(80, 100);
		check(81, 160);
		check(85, 160);
		check(90, 160);
		check(91, 200);
		check(95, 200);
		check(100, 200);
		check(101, 280);
		check(110, 280);
		check(111, 480);
		check(115, 480);
		check(120, 480);
		check(121, 680);
		check(135, 680);
		check(200, 680);
	}
	
	public static void check(int carSpeed, int fine)
	{
		if(calculateFine(carSpeed) != fine) {
			System.out.println("Неверный штраф " + fine + " для скорости " + carSpeed);
		}
		else {
			System.out.println("Штраф " + fine + " для скорости " + carSpeed + " рассчитан верно");
		}
	}
	
	public static int calculateFine(int carSpeed) {
		int fineFor1to10 = 15;
		int fineFor11to15 = 25;
		int fineFor16to20 = 35;
		int fineFor21to25 = 80;
		int fineFor26to30 = 100;
		int fineFor31to40 = 160;
		int fineFor41to50 = 200;
		int fineFor51to60 = 280;
		int fineFor61to70 = 480;
		int fineForMoreThan70 = 680;
		
		int townSpeed = 50;
		
		int overSpeed = carSpeed - townSpeed;
		
		if(overSpeed <= 0) {
			return 0;
		}
		else if(overSpeed >= 1 && overSpeed <= 10) {
			return fineFor1to10;
		}
		else if(overSpeed >= 11 && overSpeed <= 15) {
			return fineFor11to15;
		}
		else if(overSpeed >= 16 && overSpeed <= 20) {
			return fineFor16to20;
		}
		else if(overSpeed >= 21 && overSpeed <= 25) {
			return fineFor21to25;
		}
		else if(overSpeed >= 26 && overSpeed <= 30) {
			return fineFor26to30;
		}
		else if(overSpeed >= 31 && overSpeed <= 40) {
			return fineFor31to40;
		}
		else if(overSpeed >= 41 && overSpeed <= 50) {
			return fineFor41to50;
		}
		else if(overSpeed >= 51 && overSpeed <= 60) {
			return fineFor51to60;
		}
		else if(overSpeed >= 61 && overSpeed <= 70) {
			return fineFor61to70;
		}
		return fineForMoreThan70;
	}
}
```

**Задача 3**
<h1 tabindex="-1" class="heading-element" dir="auto">Кибербезопасность</h1>

**Задача 1**

![](https://github.com/user-attachments/assets/d2736852-3479-4801-a5bb-a6adb71c0e23)

**Задача 2**

Пароль kotenochekPass состоит из строчных и заглавных латинских букв, что даёт в общей сложности 52 возможных символа. Его длина составляет 14 знаков. Общее количество возможных комбинаций для такого пароля равняется 52 в 14-й степени, что приблизительно составляет 1,05 × 10²⁴ вариантов.

Согласно сервису «Стойкость пароля», на подбор данной комбинации потребуется около 8 378 769 лет. Чтобы перевести это время в секунды, необходимо умножить указанный срок на 86 400 секунд в сутках и 365 дней в году. В результате получается 264 232 859 184 000 секунд.

Если разделить общее число комбинаций (1,05 × 10²⁴) на полученное количество секунд, выйдет примерно 4 миллиарда операций в секунду. Эта цифра и отражает предполагаемую скорость перебора пароля сервисом.

**Задача 3**

![](https://github.com/user-attachments/assets/40bb623d-6fa7-4fd5-9880-b5b092365dac)

<h1 tabindex="-1" class="heading-element" dir="auto">Data Science</h1>
**Практическая работа:**

Самый точный алгоритм, который был найден это ClassificationViaRegression с точностью 80.2505%

![](https://github.com/user-attachments/assets/68555a7b-b087-444f-bdd1-e27609455119)

<h1 tabindex="-1" class="heading-element" dir="auto">Разработка iOS-приложений</h1>

<h1 tabindex="-1" class="heading-element" dir="auto">Разработка Android-приложений</h1>

**Задание 1**

**Результат:**

![](https://github.com/user-attachments/assets/5ddb2818-acdf-46fb-8971-4530de1d6b21)![](https://github.com/user-attachments/assets/c17deab9-b315-4559-a082-6f2a460caaea)

**Задание 2**

**Код:**
```html
import java.util.*
 
fun main(args: Array<String>) {
    var carSpeed = 96
    var townSpeed = 50
 
	var fineFor1to10 = 15
	var fineFor11to15 = 25
	var fineFor16to20 = 35
	var fineFor21to25 = 80
	var fineFor26to30 = 100
	var fineFor31to40 = 160
	var fineFor41to50 = 200
	var fineFor51to60 = 280
	var fineFor61to70 = 480
	var fineFor71andMore = 680
 
	var overSpeed = carSpeed - townSpeed
 
	if (overSpeed < 1) {
	    print("Скорость не превышена или превышена незначительно")
	} else if (overSpeed >= 1 && overSpeed <= 10) {
	    print("Штраф: " + fineFor1to10)
	} else if (overSpeed >= 11 && overSpeed <= 15) {
	    print("Штраф: " + fineFor11to15)
	} else if (overSpeed >= 16 && overSpeed <= 20) {
	    print("Штраф: " + fineFor16to20)
	} else if (overSpeed >= 21 && overSpeed <= 25) {
	    print("Штраф: " + fineFor21to25)
	} else if (overSpeed >= 26 && overSpeed <= 30) {
	    print("Штраф: " + fineFor26to30)
	} else if (overSpeed >= 31 && overSpeed <= 40) {
	    print("Штраф: " + fineFor31to40)
	} else if (overSpeed >= 41 && overSpeed <= 50) {
	    print("Штраф: " + fineFor41to50)
	} else if (overSpeed >= 51 && overSpeed <= 60) {
	    print("Штраф: " + fineFor51to60)
	} else if (overSpeed >= 61 && overSpeed <= 70) {
	    print("Штраф: " + fineFor61to70)
	} else {
	    print("Штраф: " + fineFor71andMore)
	}
}
```
