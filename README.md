a = 1;i = 5;
while i < 8
    for j = 1:3
        a = a * j + i;
    end
    i = i + 1;
end
disp(a);
