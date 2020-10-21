# سنبدأ بشرح الإضافات البسيطة على البرنامج
from tkinter import *
from dev_mini_excel import * #استدعينا هنا الملف الذي عملنا فيه الدوال و الذي كنا شرح في دواله قبل قليل
t = Tk()
t.geometry("370x595")
t.resizable(0,0)
t.title("mini excel")
t.iconbitmap(r"C:\Users\SeVeN\Downloads\mini excel.png")
a1 = StringVar()
a2 = StringVar()
a3 = StringVar()
a4 = StringVar()
b1 = StringVar()
b2 = StringVar()
b3 = StringVar()
b4 = StringVar()
c1 = StringVar()
c2 = StringVar()
c3 = StringVar()
c4 = StringVar()
d1 = StringVar()
d2 = StringVar()
d3 = StringVar()
d4 = StringVar()
e1 = StringVar()
e2 = StringVar()
e3 = StringVar()
e4 = StringVar()
f1 = StringVar()
f2 = StringVar()
f3 = StringVar()
f4 = StringVar()
g1 = StringVar()
g2 = StringVar()
g3 = StringVar()
g4 = StringVar()

text1= StringVar()
x = []
def run () :
    for i in x :
        if i != "" :
            eval(str(i))
        else :
            pass
def mm() :
    t.geometry("370x585")
def tfwts() :
    t.geometry("370x155")

def key(event) : 
    if event.keysym == "F1": 
        mm()
    if event.keysym == "F2":
        tfwts()
    if event.keysym == "F5" :
        run()
    if event.keysym == "F10" :
        app()
    if event.keysym == "F7" :
        repop()
    if event.keysym == "F9" :
        remall()

t.bind("<Key>",key)
t.focus_set()
en1 = Entry(t,textvariable=a1,width=6).place(x=20,y=30) ; l = Label(t,text="1",width=0).place(x=0,y=30) ; l1 = Label(t,text="A",width=6,bd=0).place(x=20,y=0)
en2 = Entry(t,width=6,textvariable=a2).place(x=20,y=60) ; l = Label(t,text="2",width=0).place(x=0,y=60)
en3 = Entry(t,width=6,textvariable=a3).place(x=20,y=90) ; l = Label(t,text="3",width=0).place(x=0,y=90)
en4 = Entry(t,width=6,textvariable=a4).place(x=20,y=120) ; l = Label(t,text="4",width=0).place(x=0,y=120)
en1 = Entry(t,width=6,textvariable=b1).place(x=70,y=30) ; l1 = Label(t,text="B",width=6,bd=0).place(x=70,y=0)
en2 = Entry(t,width=6,textvariable=b2).place(x=70,y=60)
en3 = Entry(t,width=6,textvariable=b3).place(x=70,y=90)
en4 = Entry(t,width=6,textvariable=b4).place(x=70,y=120)
en1 = Entry(t,width=6,textvariable=c1).place(x=120,y=30) ; l1 = Label(t,text="C",width=6,bd=0).place(x=120,y=0)
en2 = Entry(t,width=6,textvariable=c2).place(x=120,y=60)
en3 = Entry(t,width=6,textvariable=c3).place(x=120,y=90)
en4 = Entry(t,width=6,textvariable=c4).place(x=120,y=120)
en1 = Entry(t,width=6,textvariable=d1).place(x=170,y=30); l1 = Label(t,text="D",width=6,bd=0).place(x=170,y=0)
en2 = Entry(t,width=6,textvariable=d2).place(x=170,y=60)
en3 = Entry(t,width=6,textvariable=d3).place(x=170,y=90)
en4 = Entry(t,width=6,textvariable=d4).place(x=170,y=120)
en1 = Entry(t,width=6,textvariable=e1).place(x=220,y=30); l1 = Label(t,text="E",width=6,bd=0).place(x=220,y=0)
en2 = Entry(t,width=6,textvariable=e2).place(x=220,y=60)
en3 = Entry(t,width=6,textvariable=e3).place(x=220,y=90)
en4 = Entry(t,width=6,textvariable=e4).place(x=220,y=120)
en1 = Entry(t,width=6,textvariable=f1).place(x=270,y=30); l1 = Label(t,text="F",width=6,bd=0).place(x=270,y=0)
en2 = Entry(t,width=6,textvariable=f2).place(x=270,y=60)
en3 = Entry(t,width=6,textvariable=f3).place(x=270,y=90)
en4 = Entry(t,width=6,textvariable=f4).place(x=270,y=120)
en1 = Entry(t,width=6,textvariable=g1).place(x=320,y=30); l1 = Label(t,text="G",width=6,bd=0).place(x=320,y=0)
en2 = Entry(t,width=6,textvariable=g2).place(x=320,y=60)
en3 = Entry(t,width=6,textvariable=g3).place(x=320,y=90)
en4 = Entry(t,width=6,textvariable=g4).place(x=320,y=120)

tt1 = Entry(t,width=56,textvariable=text1) # أنشأت مربع نص لكتابة المقاطع البرمجية الخاصة بالاكسل
l = Label(t,text="المقاطع البرمجية ").place(x=170,y=150)
tt1.place(x=20,y=180)


def app() : # هذه الدالة مسؤولة عن إضافة الأسطر البرمجية المكتوبة في مربع النص السابق
    x.append(text1.get())
    script.insert(END,text1.get())
    text1.set("")
def repop() : # هذه الدالة مسؤولة عن حذف السطر البرمجي و ذلك حسب رقمه في الليست بوكس ، و يتم تحديد الرقم بمربع النص
    line = int(text1.get())-1
    x.pop(line)
    script.delete(line)
    for i in x :
        script.insert(END,i)
        text1.set("")
def remall() : # هذه الدالة تقوم بحذف جيع الأسطر البرمجية الموجودة في الليست بوكس
    x.clear()
    script.delete(0,script.size())

sc1 = Scrollbar(t) #أضفت شريط التمرير المودي

sc2 = Scrollbar(t,orient=HORIZONTAL) # أضفت شريط التمرير الأفقي

script = Listbox(t,width=45,font=("arial",10),height=20,justify="left",relief="sunken",yscrollcommand=sc1.set,xscrollcommand=sc2.set) #أنشأت ليست بوكس ليرينا الأكواد المدخلة
script.place(x=20,y=210)

sc1.pack(side=RIGHT,fill=Y)
sc1.config(command=script.yview)
sc1.place(x=340,y=310)

sc2.pack(side=LEFT,fill=X)
sc2.config(command=script.xview)
sc2.place(x=160,y=555)

my_menu = Menu(t)
t.configure(menu=my_menu)
edit_menu = Menu(my_menu)
script_menu = Menu(my_menu)
my_menu.add_cascade(label=">>>",menu=edit_menu)
my_menu.add_cascade(label="Work with scripts",menu=script_menu)
edit_menu.add_command(label="run module                     F5",command=run)
edit_menu.add_command(label="Modify scripts                 F1",command=mm)
edit_menu.add_command(label="The file without the scripts   F2",command=tfwts)
edit_menu.add_separator()
script_menu.add_separator()
script_menu.add_command(label="Add a line                    F10",command=app)
script_menu.add_command(label="Delete Line                   F7",command=repop)
script_menu.add_command(label="Delete all lines of code      F9",command=remall)

t.mainloop()
