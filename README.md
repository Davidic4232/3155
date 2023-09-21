try:
        if a < b:
            
           
raise ValueError("a має бути більшим за b")
        
       
if b == 0:
            
           
raise ZeroDivisionError("Ділення на нуль не допускається")
        
       
if b > 100:
            
           
raise IndexError("b має бути меншим за 100")
        
       
return a / b
    except ValueError as ve:
        
       
print(f"Помилка ValueError: {ve}")
        return None
    except ZeroDivisionError as zde:
        print(f"Помилка ZeroDivisionError: {zde}")
        return None
    
   
except IndexError as ie:
        print(f"Помилка IndexError: {ie}")
        
       
return None

data = {

data = {


data =


data


10: 2, 2: 5, "123": 4, 18: 0, []: 15, 8: 4}
for key in data:
    res = divider(key, data[key])
    result.append(res)


    res = divider(key, data[key])
    result

    res = divider(key, data[key

    res = divider(key, data

    res = divider(key,

    res = divider(key

    res =

    res

   
print(result)
