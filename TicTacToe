from tkinter import *
from tkinter import messagebox


game=Tk()
game.title('TicTacToe')
game.minsize(width=400,height=600)
game.maxsize(width=600,height=700)

#Title

f1=Frame(game)
f1.pack()

l1=Label(f1,text='TIC TAC TOE',fg='Orange',bg='black',font=("Calibri",40),width=17)
l1.pack()

#global variables

turn='X'
winner=False
c=0

# end button function

def end():
    game.destroy()

#restart button function

def res():
    global turn
    global winner
    global c

    turn='X'
    winner=False
    c=0

    b1['text']=''
    b2['text']=''
    b3['text']=''
    b4['text']=''
    b5['text']=''
    b6['text']=''
    b7['text']=''
    b8['text']=''
    b9['text']=''

    b1['bg']='white'
    b2['bg']='white'
    b3['bg']='white'
    b4['bg']='white'
    b5['bg']='white'
    b6['bg']='white'
    b7['bg']='white'
    b8['bg']='white'
    b9['bg']='white'



#winner check function

def win():

    global winner
    global c


    if b1['text']=='X' and b2['text']=='X' and b3['text']=='X':

        b1['bg']='green'
        b2['bg']='green'
        b3['bg']='green'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 1 WINS')
        res()

    elif b4['text']=='X' and b5['text']=='X' and b6['text']=='X':
        b4['bg']='green'
        b5['bg']='green'
        b6['bg']='green'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 1 WINS')
        res()

    elif b7['text']=='X' and b8['text']=='X' and b9['text']=='X':
        b7['bg']='green'
        b8['bg']='green'
        b9['bg']='green'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 1 WINS')
        res()

    elif b1['text']=='X' and b4['text']=='X' and b7['text']=='X':
        b1['bg']='green'
        b4['bg']='green'
        b7['bg']='green'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 1 WINS')
        res()

    elif b2['text']=='X' and b5['text']=='X' and b8['text']=='X':
        b2['bg']='green'
        b5['bg']='green'
        b8['bg']='green'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 1 WINS')
        res()

    elif b3['text']=='X' and b6['text']=='X' and b9['text']=='X':
        b3['bg']='green'
        b6['bg']='green'
        b9['bg']='green'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 1 WINS')
        res()

    elif b1['text']=='X' and b5['text']=='X' and b9['text']=='X':
        b1['bg']='green'
        b5['bg']='green'
        b9['bg']='green'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 1 WINS')
        res()

    elif b3['text']=='X' and b5['text']=='X' and b7['text']=='X':
        b3['bg']='green'
        b5['bg']='green'
        b7['bg']='green'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 1 WINS')
        res()
    elif b1['text']=='O' and b2['text']=='O' and b3['text']=='O':
        b1['bg']='red'
        b2['bg']='red'
        b3['bg']='red'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 2 WINS')
        res()

    elif b4['text']=='O' and b5['text']=='O' and b6['text']=='O':
        b4['bg']='red'
        b5['bg']='red'
        b6['bg']='red'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 2 WINS')
        res()

    elif b7['text']=='O' and b8['text']=='O' and b9['text']=='O':
        b7['bg']='red'
        b8['bg']='red'
        b9['bg']='red'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 2 WINS')
        res()

    elif b1['text']=='O' and b4['text']=='O' and b7['text']=='O':
        b1['bg']='red'
        b4['bg']='red'
        b7['bg']='red'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 2 WINS')
        res()

    elif b2['text']=='O' and b5['text']=='O' and b8['text']=='O':
        b2['bg']='red'
        b5['bg']='red'
        b8['bg']='red'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 2 WINS')
        res()

    elif b3['text']=='O' and b6['text']=='O' and b9['text']=='O':
        b3['bg']='red'
        b6['bg']='red'
        b9['bg']='red'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 2 WINS')
        res()

    elif b1['text']=='O' and b5['text']=='O' and b9['text']=='O':
        b1['bg']='red'
        b5['bg']='red'
        b9['bg']='red'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 2 WINS')
        res()

    elif b3['text']=='O' and b5['text']=='O' and b7['text']=='O':
        b3['bg']='red'
        b5['bg']='red'
        b7['bg']='red'
        winner=True
        messagebox.showinfo(title='GAME OVER',message='PLAYER 2 WINS')
        res()

    else:
        if c==9 and winner==False:
            messagebox.showinfo(title='GAME OVER',message='DRAW\nITS A TIE')
            res()



#button click function

def click(event):
    
   global turn
   global c

   b=event.widget
   
   if b['text']=='':

    if turn=='X':
        b['text']='X'
        turn='O'
        c=c+1
        win()
        
    else:
        b['text']='O'
        turn='X'
        c=c+1
        win()

        



#Board

f2=Frame(game)
f2.pack()


b1=Button(f2,text='',font=('Arial',30),width=6,height=2,bg='white',borderwidth=5)
b1.grid(row=0,column=0)
b1.bind('<Button-1>',click)

b2=Button(f2,text='',font=('Arial',30),width=6,height=2,bg='white',borderwidth=5)
b2.grid(row=0,column=1)
b2.bind('<Button-1>',click)

b3=Button(f2,text='',font=('Arial',30),width=6,height=2,bg='white',borderwidth=5)
b3.grid(row=0,column=2)
b3.bind('<Button-1>',click)

b4=Button(f2,text='',font=('Arial',30),width=6,height=2,bg='white',borderwidth=5)
b4.grid(row=1,column=0)
b4.bind('<Button-1>',click)


b5=Button(f2,text='',font=('Arial',30),width=6,height=2,bg='white',borderwidth=5)
b5.grid(row=1,column=1)
b5.bind('<Button-1>',click)


b6=Button(f2,text='',font=('Arial',30),width=6,height=2,bg='white',borderwidth=5)
b6.grid(row=1,column=2)
b6.bind('<Button-1>',click)

b7=Button(f2,text='',font=('Arial',30),width=6,height=2,bg='white',borderwidth=5)
b7.grid(row=2,column=0)
b7.bind('<Button-1>',click)

b8=Button(f2,text='',font=('Arial',30),width=6,height=2,bg='white',borderwidth=5)
b8.grid(row=2,column=1)
b8.bind('<Button-1>',click)

b9=Button(f2,text='',font=('Arial',30),width=6,height=2,bg='white',borderwidth=5)
b9.grid(row=2,column=2)
b9.bind('<Button-1>',click)


#space

f3=Frame(game)
f3.pack()

l2=Label(f3,text='',height=2)
l2.pack()



#end and restart button

f4=Frame(game)
f4.pack()


eb=Button(f4,text='QUIT GAME',bg='red',fg='black',font=('Arial',15),borderwidth=5,command=end) 
eb.grid(row=0,column=0)

l3=Label(f4,text='',width=3)
l3.grid(row=0,column=1)

rb=Button(f4,text='RESTART GAME',bg='yellow',fg='black',font=('Arial',15),borderwidth=5,command=res)
rb.grid(row=0,column=2)




game.mainloop()


