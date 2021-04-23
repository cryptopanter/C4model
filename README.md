# C4model
C4model is a methodology to express software architectures in block diagram shapes...Kind of graphical notation or expressing language for modelling soft architectures.
## 1- First level of Visualization
The zoom-out perspective of the whole system in the biggest scale. Detail isn't important here as this is your zoomed out view showing a big picture of the system landscape. The focus should be on people (actors, roles, personas, etc) and software systems rather than technologies, protocols and other low-level details. It's the sort of diagram that you could show to non-technical people.

![c4model-1st%20level.png](c4model-1st%20level.png)

So in short, each shape demonstrates below meanings:
![c4model-1st%20level-2.png](c4model-1st%20level-2.png)
.
.
.                                                                                                                                                                                                                                                                                                                                                          

**example:**
This is an example System Context diagram for a fictional Internet Banking System. It shows the people who use it, and the other software systems that the Internet Banking System has a relationship with. Personal Customers of the bank use the Internet Banking System to view information about their bank accounts, and to make payments. The Internet Banking System itself uses the bank's existing Mainframe Banking System to do this, and uses the bank's existing E-mail System to send e-mails to customers.
![c4model-1st%20level-example.png](c4model-1st%20level-example.png)

## 2- Second level of visualization 
You zoom in a bit and you are in second level. This level of visualization is shown inside a dash-line boundry with **container** blocks.Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. 
                                                                                                                                                                                   ![c4model-2nd%20level.png](c4model-2nd%20level.png)                                                                                                                                                                       
