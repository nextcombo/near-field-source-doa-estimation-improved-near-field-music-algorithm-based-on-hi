# [Near-Field Source DOA Estimation]Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants [with MATLAB Code]

\t  
MATLAB Simulation Code  
More radar and communication MATLAB codes
%FOURTH ORDER MUSIC ALOGRITHM\n%DOA ESTIMATION BY FOURTH ORDER MUSIC\nclear all;\n% close all;\nclc;\n​\nsource_number=2;% Packet count\nsensor_number=8;%Number of elements\nN_x=512; % Signal Length\nsnapshot_number=N_x;% Quick Snap Count\nw=[pi/4 pi/6].';% Signal Frequency\nl=((2*pi*3e8)/w(1)+(2*pi*3e8)/w(2))/2;% Signal wavelength\nd=0.5*l;%Element spacing\nsnr=0;% Signal-to-noise ratio\n​\nsource_doa=[-45 50];%The incident angles of two signals\nA=[exp(-j*(0:sensor_number-1)*d*2*pi*sin(source_doa(1)*pi/180)/l);exp(-j*(0:sensor_number-1)*d*2*pi*sin(source_doa(2)*pi/180)/l)].';% Array Flow Pattern\n​\ns=sqrt(10.^(snr/10))*exp(j*w*[0:N_x-1]);% Simulation signal\n%x=awgn(s,snr);\nx=A*s+(1/sqrt(2))*(randn(sensor_number,N_x)+j*randn(sensor_number,N_x));% Array receiving signal after adding Gaussian white noise\n% Calculate the cumulant of order 4\n  

## Images

![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](01.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](02.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](03.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](04.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](05.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](06.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](07.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](08.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](09.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](10.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](11.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](12.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](13.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](14.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](15.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](16.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](17.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](18.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](19.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](20.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](21.jpg)
![(Near-Field Source DOA Estimation)Improved Near-Field MUSIC Algorithm Based on Higher Order Cumulants (with MATLAB Code)](22.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
