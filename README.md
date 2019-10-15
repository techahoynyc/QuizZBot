# QuizZBot
## Description
QuizZBot forks [CoreTechR's](https://github.com/CoretechR) Raspberry Pi Zero FPV Robot and utilizes in game questions to challenge players as they race around a predefined course.

The questions are customized per player, team, or class and stored in a JSON file for easy readability.

## Requirements
The QuizZBot requires the use of [QuizZBot-Server](https://github.com/techahoynyc/QuizZBot-Server), to provide the backend infrastructure for the web-based leaderboard and database for score tracking.

## Installation
1. Copy this repository  
   ```
   git clone https://github.com/techahoynyc/QuizZBots
   ```

1. Install Node dependencies  
   ```
   ~ $ cd QuizZBot
   ~/QuizZBot $ npm install
   ```

1. Append the following lines to /etc/rc.local, so QuizZBot starts at boot  
   ```
   cd /home/pi/QuizZBot
   sudo node app.js&
   cd
   ```

## BOM

|Item|Qty|Price|Ext Price|
|---|---|---|---|
|[Raspberry Pi Zero W](https://www.adafruit.com/product/3400)|1|10|10|
|[Raspberry Pi Camera](https://www.adafruit.com/product/3099)|1|29.95|29.95|
|[DRV8833](https://www.adafruit.com/product/3297)|1|4.95|4.95|
|[2200 mAh LiPo](https://www.adafruit.com/product/1781)|1|9.95|9.95|
|[TT Motor](https://www.adafruit.com/product/3777)|2|2.95|5.9|
|[PowerBoost 1000](https://www.adafruit.com/product/2465) (Optional)|0|19.95|0|
|[MT3608](https://www.addicore.com/MT3608-Boost-Converter-p/ad300.htm)|1|1.95|1.95|
|[TP4056](https://www.amazon.com/XCSOURCE-Lithium-Battery-Charger-TE420/dp/B01DRT4PWY/ref=sr_1_3?gclid=EAIaIQobChMI872XtLL55AIVzeDICh1D6gLZEAAYASAAEgKvmvD_BwE&hvadid=252725604196&hvdev=c&hvlocphy=9004405&hvnetw=g&hvpos=1t1&hvqmt=e&hvrand=7973765980742534503&hvtargid=kwd-306287038772&hydadcr=19108_9441150&keywords=tp4056+usb+charger&qid=1569875621&s=gateway&sr=8-3)|1|1.398|1.398|
|[SPDT Switch](https://www.adafruit.com/product/805)|1|0.95|0.95|
|[USB Micro B Male Plug](https://www.adafruit.com/product/1390)|1|0.95|0.95|
|[USB Micro B Female Plug](https://www.adafruit.com/product/1829)|1|0.95|0.95|
|[16GB SD Card](https://www.amazon.com/Sandisk-Ultra-Micro-UHS-I-Adapter/dp/B073K14CVB/ref=sr_1_3?keywords=micro+sd+8gb&qid=1569876363&s=gateway&sr=8-3)|1|5.79|5.79|
