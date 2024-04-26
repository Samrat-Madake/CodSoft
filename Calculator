
from tkinter import *
from tkinter.font import Font
globals()
root = Tk()

e = Entry(root, width=73, bg="white", fg="black", borderwidth=3, border=3, highlightthickness=10,
          highlightbackground="#AAB5B4", background="#B7F1F1", font=Font(size=8, weight="bold"))
e.grid(row=0, column=0, columnspan=5)


def button_click(n):
    current = e.get()
    e.delete(0, END)
    e.insert(0, str(current) + str(n))


def button_clear():
    e.delete(0, END)


def button_add():
    no1 = e.get()
    global fno
    fno = float(no1)
    e.delete(0, END)
    global opr
    opr = "add"


def button_sub():
    no1 = e.get()
    global fno
    fno = float(no1)
    e.delete(0, END)
    global opr
    opr = "sub"


def button_mul():
    no1 = e.get()
    global fno
    fno = float(no1)
    e.delete(0, END)
    global opr
    opr = "mul"


def button_div():
    no1 = e.get()
    global fno
    fno = float(no1)
    e.delete(0, END)
    global opr
    opr = "div"


def button_equal():
    no2 = e.get()
    e.delete(0, END)
    if opr == "add":
        e.insert(0, str(fno + float(no2)))
    if opr == "sub":
        e.insert(0, str(fno - float(no2)))
    if opr == "mul":
        e.insert(0, str(fno * float(no2)))
    if opr == "div":
        e.insert(0, str(fno / float(no2)))


button1 = Button(root, text="1", fg="blue", borderwidth=3, padx=49, pady=20, background="#C9CECE", command=lambda: button_click(1))
button2 = Button(root, text="2", fg="blue", borderwidth=3, padx=49, pady=20, background="#C9CECE", command=lambda: button_click(2))
button3 = Button(root, text="3", fg="blue", borderwidth=3, padx=49, pady=20, background="#C9CECE", command=lambda: button_click(3))

button4 = Button(root, text="4", fg="blue", borderwidth=3,padx=49, pady=20, background="#C9CECE", command=lambda: button_click(4))
button5 = Button(root, text="5", fg="blue", borderwidth=3,padx=49, pady=20, background="#C9CECE", command=lambda: button_click(5))
button6 = Button(root, text="6", fg="blue", borderwidth=3, padx=49, pady=20, background="#C9CECE", command=lambda: button_click(6))

button7 = Button(root, text="7", fg="blue", borderwidth=3, padx=49, pady=20, background="#C9CECE",command=lambda: button_click(7))
button8 = Button(root, text="8", fg="blue", borderwidth=3, padx=49, pady=20, background="#C9CECE", command=lambda: button_click(8))
button9 = Button(root, text="9", fg="blue", borderwidth=3, padx=49, pady=20, background="#C9CECE", command=lambda: button_click(9))

button0 = Button(root, text="0", fg="blue", padx=64, borderwidth=3, pady=20, background="#C9CECE", command=lambda: button_click(0))
button_dot = Button(root, text=".", fg="blue", borderwidth=3, padx=40, pady=20, background="#C9CECE", command=lambda: button_click("."))

button_Add = Button(root, text="+", fg="blue", borderwidth=3, padx=40, pady=20, background="#C9CECE", command=button_add)
button_minus = Button(root, text="-", fg="blue", borderwidth=3, padx=40, pady=20, background="#C9CECE", command=button_sub)
button_multiply = Button(root, text="*", fg="blue", borderwidth=3, padx=40, pady=20, background="#C9CECE", command=button_mul)
button_divide = Button(root, text="/", fg="blue", borderwidth=3, padx=40, pady=20, background="#C9CECE", command=button_div)

button_clear = Button(root, text="Clear", fg="blue", borderwidth=3, padx=168, pady=15, background="#C9CECE", command=button_clear)
button_Equal = Button(root, text="=", fg="blue", borderwidth=3, padx=105, pady=20, border=3, background="#C9CECE", command=button_equal)

button1.grid(row=5, column=0)
button2.grid(row=5, column=1)
button3.grid(row=5, column=2)

button4.grid(row=4, column=0)
button5.grid(row=4, column=1)
button6.grid(row=4, column=2)

button7.grid(row=3, column=0)
button8.grid(row=3, column=1)
button9.grid(row=3, column=2)
button0.grid(row=6, column=0, columnspan=2, sticky=W)
button_dot.grid(row=6, column=1, sticky=E)

button_clear.grid(row=2, column=0, columnspan=3)
button_Equal.grid(row=6, column=2, columnspan=3, sticky=E)

button_Add.grid(row=5, column=4)
button_minus.grid(row=4, column=4)
button_multiply.grid(row=3, column=4)
button_divide.grid(row=2, column=4)

root.mainloop()
