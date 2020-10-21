#استدعيت المكتبات التي احتاجها
import datetime
import time
import calendar
import os
from math import * #استدعينا هنا مكتبة الخاصة بالعمليات الرياضية
from tkinter import messagebox
def if_(chartt,if_true_eval) : #عملت دالة شرطية
    if chartt == True :
        eval(str(if_true_eval))
def create_folder(name_of_folder,massar_elamel) : #دالة لإنشاء مجلد
    os.chdir(r"{}".format(massar_elamel))
    os.mkdir(name_of_folder)
def create_file(nof,me) : #دالة لإنشاء ملف
    os.chdir(me)
    open(nof,"x")
date = datetime.datetime.now()
today = f"{date.year}\{date.month}\{date.day}" #متغير خاص بتاريخ اليوم
Time = f"{date.hour}:{date.minute}:{date.second}" #متغير خاص بالوقت الآن
def message(n,o,t) : # دالة لإرسال رسالة خطأ أو تحذير أو معلومة حسب المدخل الأول و الشروط
    if n == "info" :
        messagebox.showinfo(o,t)
    elif n == "error" :
        messagebox.showerror(o,t)
    elif n == "warning" :
        messagebox.showwarning(o,t)
    else :
        messagebox.showerror("خطأ","لا يوجد نوع رسالة مماثل للذي أدخلته")
def AND(x,y) : #أضفت هنا دالة للعبارات المنطقية و تعمل عمل and
    if (x and y) == True :
        return True
    if (x and y) == False :
        return False
def OR(x,y) : #أضفت هنا دالة للعبارات المنطقية و تعمل عمل or
    if (x or y) == True :
        return True
    if (x or y) == False :
        return False
