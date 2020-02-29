from tkinter import *

root= tk()
root.title("ventana principal")
root.resizable(0,0)# desactivar la redimensiones
root.config(bg="orange")
root.config(bd=20)
root.config(cursor="arrow") ______________

frame= frame(root) /frame= frame(root,width=380,height=320,bg="red") 
frame.pack(fill="both",expand=1)
frame.config(bg="lightblue")
frame.config(width=380,height=320)
frame.config(cursor="pirate")
frame.config(relief="sunken")
_______________
label1=label(frame,text="esto es un label dentro del frame
label1.pack()
label2=label(root,text="esto es un label")
label2.pack






root.mainloop()
