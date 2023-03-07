from tkinter import *


root=Tk()
root.geometry('450x550')
root.title("Englih Dictonary")
root.configure(background="silver")

#Entry widget object

textin=StringVar()

#Dictionaries

exlist={'word':'meaning','hello':'an expression of greeting','noun':'a word (other than a pronoun) used to identify any of a class of people, places, or things (common noun)'}


# submit button function
def clk():
     entered = ent.get()
     output.delete(0.0,END)
     try:
          textin = exlist[entered]
     except:
          textin = 'SORRY no meaning found \n'
     output.insert(0.0,textin)


     

     

mla=Label(root,text="DICTONARY ",font=("Algerian",15))
mla.grid(row=0,column=1,sticky=N)
mla4=Label(root,text="<= Enter word Below =>")
mla4.grid(row=2,column=1,sticky=N)

lab=Label(root,text='Word :',font=('Time 20 '))
lab.grid(row=3,column=0,sticky=W)

ent=Entry(root,width=20,textvar=textin,bg='white',font=('Time 20 '))
ent.grid(row=3,column=1,sticky=W)


but=Button(root,padx=2,pady=2,text='Submit',command=clk,bg='white')
but.place(x=200,y=90)


output=Text(root,width=20,height=8,font=('Time 14 bold'),fg="black")
output.place(x=100,y=200)


labb=Label(root,text='Meaning',font=('Time 17 '))
labb.place(x=0,y=180)


root.mainloop()
