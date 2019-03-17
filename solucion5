function [t,x] = call_Ejercicio5
    tspan = [0; 50];
    y0 = [100; 8];
    [t, x] = ode45(@Ejercicio5, tspan, y0);
    subplot(2,1,1);
    plot(t,x(:,1))
    subplot(2,1,2);
    plot(t,x(:,2))
end
