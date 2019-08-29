# scatter plot
plt.figure(figsize=(5,5),facecolor='red')

x=np.linspace(0,10,14)

plt.scatter(x,np.sin(x),color='darkorange')

plt.title('scatter plot')

plt.xlabel('x axis')

plt.ylabel('y axis')




# sub plots in python 

plt.figure(figsize=(16,9),facecolor='red')

plt.subplot(1,2,1)

x=np.linspace(0,10,14)

plt.plot(x,np.sin(x),linestyle='--',color='darkorange',marker='>')

plt.ylim(0,2)

plt.xlim(0,10)

plt.title('scatter plot')

plt.xlabel('x axis')

plt.ylabel('y axis')

plt.subplot(1,2,2)

plt.scatter(x=np.random.normal(0,1,10),y=range(10),color='red',marker='*')

plt.title('scatter plot')

plt.xlabel('x axis')

plt.ylabel('y axis')

plt.grid(color='black')

    
