# Calculation-of-String-Efficiency-In-Transmission-line
In this code we can calculate the string efficiency of Line by using the V, Disc(Insulator)

v=input("v of the Transmission line");
Vp=v/1.73
k=input("Enter the value of k");
S=input("Enter the value of S");
V1=(Vp)/(3+(4*k)+(k^2));
V2=V1*(1+k);
V3=V1*(1+(3*k)+(k^2));
E=((Vp)/(V3*S))*100);
fprintf("The value of Effi= %d",E);
