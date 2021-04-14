import matplotlib.pyplot as plt
from matplotlib.font_manager import FontProperties
import pandas as pd
font = FontProperties(fname=r"C:\Windows\Fonts\simhei.ttf", size=14)  
salary = pd.read_excel(r'C:\DataTestPY\HisData.xlsx', usecols="F:F")
group = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150, 160, 170, 180]
plt.hist(salary, group, histtype='bar', rwidth=0.8)
plt.legend()
plt.xlabel('PM2.5 disturbution')
plt.ylabel('PM2.5 index')
plt.title(u'PM2.5 Inspection by Histogram', FontProperties=font)
plt.show()
