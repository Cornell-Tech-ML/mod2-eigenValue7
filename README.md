[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

# Simple

Epoch 500/500. Time per epoch: 0.039s. Time left: 0.00s.
number of points: 50, LR: 0.1, 

Epoch: 0/500, loss: 0, correct: 0
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 35.580156303537386, correct: 28
Epoch: 20/500, loss: 34.83482600646951, correct: 28
Epoch: 30/500, loss: 34.57891385679886, correct: 28
Epoch: 40/500, loss: 34.45527535625563, correct: 28
Epoch: 50/500, loss: 34.36618382344308, correct: 28
Epoch: 60/500, loss: 34.28531371484072, correct: 28
Epoch: 70/500, loss: 34.20396143308417, correct: 28
Epoch: 80/500, loss: 34.11737241816871, correct: 28
Epoch: 90/500, loss: 34.021358433258946, correct: 28
Epoch: 100/500, loss: 33.91135521277198, correct: 28
Epoch: 110/500, loss: 33.78201846524199, correct: 28
Epoch: 120/500, loss: 33.626903952523676, correct: 28
Epoch: 130/500, loss: 33.44047388879493, correct: 28
Epoch: 140/500, loss: 33.21472832513873, correct: 28
Epoch: 150/500, loss: 32.9366589958503, correct: 28
Epoch: 160/500, loss: 32.59178455239874, correct: 28
Epoch: 170/500, loss: 32.166147638724254, correct: 28
Epoch: 180/500, loss: 31.63430851477336, correct: 28
Epoch: 190/500, loss: 30.966234856440963, correct: 31
Epoch: 200/500, loss: 30.126098360874284, correct: 36
Epoch: 210/500, loss: 29.07193781552031, correct: 38
Epoch: 220/500, loss: 27.75909331262232, correct: 39
Epoch: 230/500, loss: 26.151303144012974, correct: 41
Epoch: 240/500, loss: 24.304823513923942, correct: 42
Epoch: 250/500, loss: 22.244315373828105, correct: 44
Epoch: 260/500, loss: 20.17959198756594, correct: 45
Epoch: 270/500, loss: 18.136316530928756, correct: 45
Epoch: 280/500, loss: 16.195003432999705, correct: 46
Epoch: 290/500, loss: 14.470657160594222, correct: 46
Epoch: 300/500, loss: 12.933604344123136, correct: 47
Epoch: 310/500, loss: 11.60292406385458, correct: 48
Epoch: 320/500, loss: 10.453369363966678, correct: 48
Epoch: 330/500, loss: 9.471861303453238, correct: 49
Epoch: 340/500, loss: 8.639028230002296, correct: 49
Epoch: 350/500, loss: 7.941158054578147, correct: 50
Epoch: 360/500, loss: 7.361654634648573, correct: 50
Epoch: 370/500, loss: 6.851802864268291, correct: 50
Epoch: 380/500, loss: 6.39774043994412, correct: 50
Epoch: 390/500, loss: 5.992212218141629, correct: 50
Epoch: 400/500, loss: 5.628195970927404, correct: 50
Epoch: 410/500, loss: 5.300698221735525, correct: 50
Epoch: 420/500, loss: 5.003806609157698, correct: 50
Epoch: 430/500, loss: 4.733808501576251, correct: 50
Epoch: 440/500, loss: 4.487615011673732, correct: 50
Epoch: 450/500, loss: 4.261948595360839, correct: 50
Epoch: 460/500, loss: 4.054518632806395, correct: 50
Epoch: 470/500, loss: 3.8633666907889004, correct: 50
Epoch: 480/500, loss: 3.686807020299086, correct: 50
Epoch: 490/500, loss: 3.5243147034759255, correct: 50
Epoch: 500/500, loss: 3.3738378047487414, correct: 50

#diag
number of points: 100, LR: 0.5
Epoch 1000/1000. Time per epoch: 0.073s. Time left: 0.00s.

Epoch: 0/1000, loss: 0, correct: 0
Epoch: 10/1000, loss: 55.51374734353828, correct: 91
Epoch: 20/1000, loss: 39.02227180361871, correct: 91
Epoch: 30/1000, loss: 34.58675232988784, correct: 91
Epoch: 40/1000, loss: 33.075208243647005, correct: 91
Epoch: 50/1000, loss: 32.21982407585089, correct: 91
Epoch: 60/1000, loss: 31.520552521056764, correct: 91
Epoch: 70/1000, loss: 30.84866907237229, correct: 91
Epoch: 80/1000, loss: 30.297783400926587, correct: 91
Epoch: 90/1000, loss: 30.090400029835845, correct: 91
Epoch: 100/1000, loss: 29.999334940828657, correct: 91
Epoch: 0/1000, loss: 0, correct: 0
Epoch: 10/1000, loss: 27.463001492436877, correct: 91
Epoch: 20/1000, loss: 24.20607242066349, correct: 91
Epoch: 30/1000, loss: 21.48007845823175, correct: 91
Epoch: 40/1000, loss: 19.111167720221673, correct: 91
Epoch: 50/1000, loss: 17.052228031887413, correct: 91
Epoch: 60/1000, loss: 15.371112704138902, correct: 91
Epoch: 70/1000, loss: 14.145299001873795, correct: 91
Epoch: 80/1000, loss: 12.822089204948501, correct: 91
Epoch: 90/1000, loss: 11.813566790005336, correct: 91
Epoch: 100/1000, loss: 10.77561642189946, correct: 91
Epoch: 110/1000, loss: 9.952178988806942, correct: 91
Epoch: 120/1000, loss: 9.207385834919604, correct: 100
Epoch: 130/1000, loss: 8.530828032303013, correct: 100
Epoch: 140/1000, loss: 7.905961961008424, correct: 100
Epoch: 150/1000, loss: 7.32847392085008, correct: 100
Epoch: 160/1000, loss: 6.787751644937992, correct: 100
Epoch: 170/1000, loss: 6.285015428556216, correct: 100
Epoch: 180/1000, loss: 5.81851028523876, correct: 100
Epoch: 190/1000, loss: 5.392068846390984, correct: 100
Epoch: 200/1000, loss: 4.721320816058534, correct: 100
Epoch: 210/1000, loss: 4.380225442764597, correct: 100
Epoch: 220/1000, loss: 4.071146479493343, correct: 100
Epoch: 230/1000, loss: 3.7885329863527306, correct: 100
Epoch: 240/1000, loss: 3.5330060664143152, correct: 100
Epoch: 250/1000, loss: 3.0579370869792206, correct: 100
Epoch: 260/1000, loss: 2.950508707363011, correct: 100
Epoch: 270/1000, loss: 2.6990779094862947, correct: 100
Epoch: 280/1000, loss: 2.5946250456331352, correct: 100
Epoch: 290/1000, loss: 2.396103639004777, correct: 100
Epoch: 300/1000, loss: 2.2725163405054327, correct: 100
Epoch: 310/1000, loss: 2.159098912482592, correct: 100
Epoch: 320/1000, loss: 2.054760028961039, correct: 100
Epoch: 330/1000, loss: 1.9585522214169846, correct: 100
Epoch: 340/1000, loss: 1.8697516685769764, correct: 100
Epoch: 350/1000, loss: 1.7875174983945354, correct: 100
Epoch: 360/1000, loss: 1.7112960757314002, correct: 100
Epoch: 370/1000, loss: 1.6404159780269656, correct: 100
Epoch: 380/1000, loss: 1.5743831516972726, correct: 100
Epoch: 390/1000, loss: 1.5127593869374423, correct: 100
Epoch: 400/1000, loss: 1.4551545648955728, correct: 100
Epoch: 410/1000, loss: 1.4012204934872803, correct: 100
Epoch: 420/1000, loss: 1.3506456540424074, correct: 100
Epoch: 430/1000, loss: 1.3031507030930638, correct: 100
Epoch: 440/1000, loss: 1.2584846046868525, correct: 100
Epoch: 450/1000, loss: 1.2164212924403621, correct: 100
Epoch: 460/1000, loss: 1.1767567790711764, correct: 100
Epoch: 470/1000, loss: 1.139386215630442, correct: 100
Epoch: 480/1000, loss: 1.1041924292322665, correct: 100
Epoch: 490/1000, loss: 1.0710710727601334, correct: 100
Epoch: 500/1000, loss: 1.039225278425313, correct: 100
Epoch: 510/1000, loss: 1.0092973188483647, correct: 100
Epoch: 520/1000, loss: 0.9806152423932075, correct: 100
Epoch: 530/1000, loss: 0.9565308185801187, correct: 100
Epoch: 540/1000, loss: 0.9278032755323191, correct: 100
Epoch: 550/1000, loss: 0.9059502500117721, correct: 100
Epoch: 560/1000, loss: 0.8798703596348437, correct: 100
Epoch: 570/1000, loss: 0.8599665513397358, correct: 100
Epoch: 580/1000, loss: 0.8388096393486645, correct: 100
Epoch: 590/1000, loss: 0.8162937088382999, correct: 100
Epoch: 600/1000, loss: 0.7966342640132683, correct: 100
Epoch: 610/1000, loss: 0.777918374122654, correct: 100
Epoch: 620/1000, loss: 0.7622065674022077, correct: 100
Epoch: 630/1000, loss: 0.7432458765859378, correct: 100
Epoch: 640/1000, loss: 0.7267164486493807, correct: 100
Epoch: 650/1000, loss: 0.7125883543884332, correct: 100
Epoch: 660/1000, loss: 0.6958014891625668, correct: 100
Epoch: 670/1000, loss: 0.6814347792445868, correct: 100
Epoch: 680/1000, loss: 0.6685390879249216, correct: 100
Epoch: 690/1000, loss: 0.6535915831297773, correct: 100
Epoch: 700/1000, loss: 0.6411305276842182, correct: 100
Epoch: 710/1000, loss: 0.6292095657948568, correct: 100
Epoch: 720/1000, loss: 0.6158299148835843, correct: 100
Epoch: 730/1000, loss: 0.6050498508551175, correct: 100
Epoch: 740/1000, loss: 0.5939127339642598, correct: 100
Epoch: 750/1000, loss: 0.5820532474351021, correct: 100
Epoch: 760/1000, loss: 0.5715461913200937, correct: 100
Epoch: 770/1000, loss: 0.5622850139326314, correct: 100
Epoch: 780/1000, loss: 0.5528083587991989, correct: 100
Epoch: 790/1000, loss: 0.5433132142203337, correct: 100
Epoch: 800/1000, loss: 0.5340386109614114, correct: 100
Epoch: 810/1000, loss: 0.5250500742756763, correct: 100
Epoch: 820/1000, loss: 0.5163360414083077, correct: 100
Epoch: 830/1000, loss: 0.5078846482042361, correct: 100
Epoch: 840/1000, loss: 0.4996846780450222, correct: 100
Epoch: 850/1000, loss: 0.4913881902299881, correct: 100
Epoch: 860/1000, loss: 0.4830485414101908, correct: 100
Epoch: 870/1000, loss: 0.47653573724241793, correct: 100
Epoch: 880/1000, loss: 0.4692716043806988, correct: 100
Epoch: 890/1000, loss: 0.4613225179147173, correct: 100
Epoch: 900/1000, loss: 0.45558470795949507, correct: 100
Epoch: 910/1000, loss: 0.4478384293642031, correct: 100
Epoch: 920/1000, loss: 0.4423811000911289, correct: 100
Epoch: 930/1000, loss: 0.4358919062625493, correct: 100
Epoch: 940/1000, loss: 0.4299684765645638, correct: 100
Epoch: 950/1000, loss: 0.4239870617987304, correct: 100
Epoch: 960/1000, loss: 0.41815493871581766, correct: 100
Epoch: 970/1000, loss: 0.41246976222457404, correct: 100
Epoch: 980/1000, loss: 0.40692633887588986, correct: 100
Epoch: 990/1000, loss: 0.40151962067205443, correct: 100
Epoch: 1000/1000, loss: 0.39624478961910153, correct: 100

#split
number of points: 150, LR: 1.0
Epoch 800/800. Time per epoch: 0.105s. Time left: 0.00s.

Epoch: 0/800, loss: 0, correct: 0
Epoch: 10/800, loss: 101.5540914914386, correct: 90
Epoch: 20/800, loss: 101.36043467479857, correct: 90
Epoch: 30/800, loss: 101.19502772288094, correct: 90
Epoch: 40/800, loss: 101.01930489968053, correct: 90
Epoch: 50/800, loss: 100.71521888052514, correct: 90
Epoch: 60/800, loss: 100.15060099637111, correct: 90
Epoch: 70/800, loss: 99.27913630491256, correct: 90
Epoch: 80/800, loss: 97.3265780064586, correct: 90
Epoch: 90/800, loss: 92.48984116168843, correct: 104
Epoch: 100/800, loss: 87.75182875166061, correct: 103
Epoch: 110/800, loss: 94.77137748592946, correct: 90
Epoch: 120/800, loss: 90.92531898523413, correct: 98
Epoch: 130/800, loss: 87.84003684273227, correct: 100
Epoch: 140/800, loss: 85.75818080520726, correct: 104
Epoch: 150/800, loss: 82.19598989557454, correct: 105
Epoch: 160/800, loss: 79.86189852963778, correct: 108
Epoch: 170/800, loss: 78.6015565786848, correct: 110
Epoch: 180/800, loss: 75.4909835177576, correct: 114
Epoch: 190/800, loss: 74.47105152050159, correct: 114
Epoch: 200/800, loss: 73.75240256502155, correct: 114
Epoch: 210/800, loss: 73.30852141651998, correct: 114
Epoch: 220/800, loss: 71.67430570171632, correct: 115
Epoch: 230/800, loss: 67.93212213505497, correct: 117
Epoch: 240/800, loss: 65.30542025789741, correct: 117
Epoch: 250/800, loss: 65.5431081563378, correct: 115
Epoch: 260/800, loss: 77.26513882039367, correct: 114
Epoch: 270/800, loss: 64.80754127333076, correct: 118
Epoch: 280/800, loss: 64.21472640499799, correct: 123
Epoch: 290/800, loss: 34.457308540311125, correct: 139
Epoch: 300/800, loss: 40.63517097054286, correct: 126
Epoch: 310/800, loss: 90.54839859224273, correct: 105
Epoch: 320/800, loss: 24.980924424330606, correct: 147
Epoch: 330/800, loss: 37.22104058090547, correct: 125
Epoch: 340/800, loss: 64.71217609103341, correct: 111
Epoch: 350/800, loss: 93.54741334371654, correct: 102
Epoch: 360/800, loss: 34.36877219927612, correct: 132
Epoch: 370/800, loss: 30.785634818157646, correct: 142
Epoch: 380/800, loss: 20.952283019961147, correct: 144
Epoch: 390/800, loss: 21.107532811653932, correct: 148
Epoch: 400/800, loss: 27.348599171313783, correct: 148
Epoch: 410/800, loss: 101.60797114586661, correct: 101
Epoch: 420/800, loss: 23.96127944017684, correct: 138
Epoch: 430/800, loss: 25.6686466409639, correct: 147
Epoch: 440/800, loss: 53.05794460337163, correct: 124
Epoch: 450/800, loss: 21.052901353749515, correct: 142
Epoch: 460/800, loss: 18.91834006464158, correct: 148
Epoch: 470/800, loss: 153.74017861666974, correct: 85
Epoch: 480/800, loss: 49.70944005367247, correct: 130
Epoch: 490/800, loss: 13.930364125558347, correct: 147
Epoch: 500/800, loss: 21.491971909734737, correct: 138
Epoch: 510/800, loss: 22.276828424119866, correct: 140
Epoch: 520/800, loss: 15.076858944383986, correct: 145
Epoch: 530/800, loss: 32.9799306778762, correct: 134
Epoch: 540/800, loss: 14.741363998091952, correct: 148
Epoch: 550/800, loss: 69.41942920555398, correct: 118
Epoch: 560/800, loss: 11.775273306439178, correct: 147
Epoch: 570/800, loss: 11.003198579475947, correct: 147
Epoch: 580/800, loss: 27.61229007672304, correct: 137
Epoch: 590/800, loss: 16.513561460976604, correct: 148
Epoch: 600/800, loss: 9.624338345767107, correct: 150
Epoch: 610/800, loss: 8.171970208221586, correct: 150
Epoch: 620/800, loss: 7.777112395350371, correct: 147
Epoch: 630/800, loss: 16.189285175768305, correct: 144
Epoch: 640/800, loss: 14.287573101378399, correct: 147
Epoch: 650/800, loss: 8.867747432152738, correct: 150
Epoch: 660/800, loss: 7.673252432019277, correct: 150
Epoch: 670/800, loss: 6.793875365669487, correct: 150
Epoch: 680/800, loss: 6.119440753188823, correct: 150
Epoch: 690/800, loss: 5.629496285526099, correct: 150
Epoch: 700/800, loss: 11.389353994566768, correct: 145
Epoch: 710/800, loss: 11.276640165674602, correct: 147
Epoch: 720/800, loss: 8.001274139710063, correct: 148
Epoch: 730/800, loss: 6.997479686483199, correct: 148
Epoch: 740/800, loss: 6.698444954933926, correct: 147
Epoch: 750/800, loss: 76.86871401774818, correct: 131
Epoch: 760/800, loss: 23.435362081181896, correct: 137
Epoch: 770/800, loss: 9.140364072209271, correct: 150
Epoch: 780/800, loss: 7.479363457439376, correct: 150
Epoch: 790/800, loss: 6.579022847421649, correct: 150
Epoch: 800/800, loss: 5.908137399247399, correct: 150

#xor 
number of points: 100, LR: 1.0, Hidden Layers: 4.0
Epoch 500/500. Time per epoch: 0.160s. Time left: 0.00s.

Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 69.76128276366696, correct: 54
Epoch: 20/500, loss: 69.74445078565078, correct: 54
Epoch: 30/500, loss: 69.71800171489663, correct: 54
Epoch: 40/500, loss: 69.66222499362284, correct: 54
Epoch: 50/500, loss: 69.550309782565, correct: 54
Epoch: 60/500, loss: 69.35934702956033, correct: 54
Epoch: 70/500, loss: 69.01904707183034, correct: 54
Epoch: 80/500, loss: 68.3827276245001, correct: 54
Epoch: 90/500, loss: 67.0164067486911, correct: 55
Epoch: 100/500, loss: 64.28539811498706, correct: 75
Epoch: 110/500, loss: 65.82527985824784, correct: 68
Epoch: 120/500, loss: 67.04333558857222, correct: 60
Epoch: 130/500, loss: 67.0965413659578, correct: 60
Epoch: 140/500, loss: 60.756608542077736, correct: 71
Epoch: 150/500, loss: 57.476879668793366, correct: 74
Epoch: 160/500, loss: 65.72093721141614, correct: 61
Epoch: 170/500, loss: 51.9926750201054, correct: 76
Epoch: 180/500, loss: 60.16434395342628, correct: 62
Epoch: 190/500, loss: 48.53312558365525, correct: 82
Epoch: 200/500, loss: 56.25100950591046, correct: 72
Epoch: 210/500, loss: 83.31918775843378, correct: 50
Epoch: 220/500, loss: 42.09956292843132, correct: 92
Epoch: 230/500, loss: 60.253928804998246, correct: 66
Epoch: 240/500, loss: 40.347695419967245, correct: 89
Epoch: 250/500, loss: 59.75804382694646, correct: 61
Epoch: 260/500, loss: 54.184425016111526, correct: 72
Epoch: 270/500, loss: 53.09792126172998, correct: 74
Epoch: 280/500, loss: 51.85744610802867, correct: 73
Epoch: 290/500, loss: 50.78305812634051, correct: 69
Epoch: 300/500, loss: 48.38312203579561, correct: 73
Epoch: 310/500, loss: 34.19039228783773, correct: 93
Epoch: 320/500, loss: 45.71474221532934, correct: 82
Epoch: 330/500, loss: 49.31456607692227, correct: 74
Epoch: 340/500, loss: 30.862957340441138, correct: 90
Epoch: 350/500, loss: 52.89975461870159, correct: 76
Epoch: 360/500, loss: 23.569031271849347, correct: 95
Epoch: 370/500, loss: 31.21341038410431, correct: 87
Epoch: 380/500, loss: 50.32059536555154, correct: 79
Epoch: 390/500, loss: 22.405643843947633, correct: 94
Epoch: 400/500, loss: 24.556611997303918, correct: 91
Epoch: 410/500, loss: 20.444906196601686, correct: 94
Epoch: 420/500, loss: 38.08510791155278, correct: 86
Epoch: 430/500, loss: 51.428685449705696, correct: 78
Epoch: 440/500, loss: 30.20896418553236, correct: 85
Epoch: 450/500, loss: 28.813976323547628, correct: 85
Epoch: 460/500, loss: 17.500110760721597, correct: 96
Epoch: 470/500, loss: 37.15071101272783, correct: 86
Epoch: 480/500, loss: 17.360075220896984, correct: 95
Epoch: 490/500, loss: 16.789849669846017, correct: 97
Epoch: 500/500, loss: 26.27677451876731, correct: 90