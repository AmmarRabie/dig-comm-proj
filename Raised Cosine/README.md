# Digital Communication Project
Simulate the performance of different modulation schemes in an AWGN environment with applying **raised cosine pulse shaping**:
- [BPSK](#BPSK)
- [QPSK](#QPSK)
- [FSK](#FSK)
- [QAM16](#QAM16)
- [QAM64](#QAM64)

 # Common instructions:
 1. Open matlab
 2. Open bit error tool by Typing `bertool` in the matlab command window
 3. From theoretical tab:
    1. put the Eb/No = -10:10
    2. Channel type = AWGN
    3. modulation type = [PSK, FSK or QAM based on required modulation technique]
    4. modulation order = (BPSK:2, FSK:2, QPSK:4, QAM16: 16, QAM64:64)
    5. click plot button to get the theoretical curve
 4. In the Monte Carlo tap do the following:
    1. put the Eb/No = -10:10
    2. click browse and choose the file based on required modulation scheme (the file of slx extension)
    3. make variable name = [name of the file]
    4. click run button to get the simulated curve


# <a id="BPSK"></a>BPSK
## Plot before noise
![before](images/BPSK-before.jpg)
## Plot after noise
![after](images/BPSK-after.jpg)
## BER Curve
![curve](images/BPSK-curve.jpg)


# <a id="QPSK"></a> QPSK

## Plot before noise
![before](images/QPSK-before.jpg)
## Plot after noise
![after](images/QPSK-after.jpg)
## BER Curve
![curve](images/QPSK-curve.jpg)


## <a id="FSK"></a> FSK

## Plot before noise
![before](images/FSK-before.jpg)
## Plot after noise
![after](images/FSK-after.jpg)
## BER Curve
![curve](images/FSK-curve.jpg)



## <a id="QAM16"></a>QAM16

## Plot before noise
![before](images/QAM16-before.jpg)
## Plot after noise
![after](images/QAM16-after.jpg)
## BER Curve
![curve](images/QAM16-curve.jpg)


## <a id="QAM64"></a>QAM64
![before](images/QAM64-before.jpg)
## Plot after noise
![after](images/QAM64-after.jpg)
## BER Curve
![curve](images/QAM64-curve.jpg)