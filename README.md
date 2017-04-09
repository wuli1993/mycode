# mycode 条件结构练习
height = float(input('请输入身高(m)：'))
weight = float(input('请输入体重(kg)：'))
BMI = float(weight / (height*height))
b='您的BMI指数是%.2f，' % BMI
if BMI < 18.5:
      print(b, '过轻')
elif BMI < 25:
      print(b, '正常')
elif BMI < 28:
      print(b, '过重')
elif BMI < 32:
      print(b, '肥胖')
else:
      print(b, '严重肥胖')
