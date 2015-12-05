# funcion-rocket-1
%Funcion Cohete
for t=0:2:100 %Rango de valores que toma el tiempo permitidos de 0 a 100 en un incremento de 2
    altura=60+(2.13*t^2)-(0.0013*t^4)+0.000034*t^4.751;%Ecuacion de altura
    
    fprintf('la altura es %f en el tiempo %f. \n',altura,t)% Impresion de los valores de la altura y el tiempo en un instante de tiempo
    
end
