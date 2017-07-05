# [Berkeley DeepRL course](http://rll.berkeley.edu/deeprlcourse/) Homework

## Result on HW1

- With given hyperparameter, I was able to get the results below.

|       Envs    | Expert Reward Mean(std) | Behavior Cloning | DAgger |
|:-------------:|------------------------:|-----------------:|-------:|
|Ant-v1         | 4802.707680(83.771094)  | 907.181835(1.765161)| 515.062574(2.715588)|
|HalfCheetah-v1 | 4126.918521(75.359644)  | 4138.678126(68.150322)| 4112.790801(61.154570)|
|Hopper-v1      | 3777.821053(3.777258)   | 3776.561768(3.774195)| 3783.089913(4.757560)|
|Humanoid-v1    | 10429.852380(51.341089) | 367.905249(19.686467)| 313.611396(11.924769)|
|Reacher-v1     | -3.894341(1.580284)     | -13.215903(3.970900)| -13.954921(4.214502)|
|Walker2d-v1    | 5523.786277(50.682188)  | 4305.271517(1845.930949)| 5516.414445(51.565740)|

- HalfCheetah, Hopper, Walker2d were trainable and others were not with fixed hyperparameters
- In all three successful cases, DAgger gives better performance (higher rewards, lower std.)

## TODO

- [x] HW 1; Imitation Learning, Dagger
- [] HW 2
- [] HW 3
- [] HW 4
- [] HW 5
