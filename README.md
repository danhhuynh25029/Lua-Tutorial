# Lua-Tutorial
### Xuất:
```lua
  io.write("Hello world")
  print("Hello world")
```
### Nhập:
```lua
  io.read()
```
### Điều kiện:
```lua
  age = 20
  if age == 20 then
    print("Ban da 20 tuoi")
  elseif age == 18 then
    print("Ban da du 18 tuoi")
  else
    print("Ban chua du tuoi")
  end
```
### Vòng lặp:
```lua
--Vòng lặp for
  for i=1,10 do
    print(i)
  end
--Vòng lặp while
  i = 1
  while i <= 10 do
    print(i)
  end
```  
### Hàm:
```lua
  function Sum(num1,num2)
    return num1+num2
  end
```
### Đối tượng:
```lua
  Animal = {}
  function Aniaml:new(name,age)
    self.name = name
    self.age = age
    return self
  end
  dog = Animal:new("Milo",1)
  print(dog.name)
```
