#!/usr/bin/env python
# coding: utf-8

# In[1]:


# Master Math by Coding in Python - Mike X Cohen
# Harmonograph: https://en.wikipedia.org/wiki/Harmonograph


# In[2]:


import numpy as np
import matplotlib.pyplot as plt


# In[3]:


n = 10000
t = np.logspace(np.log10(10),np.log10(500),n)


# In[4]:


A = [  1, 1, 1.5, 1.5 ]
d = [ .004, .001, .002, .0015 ]
f = [   3, 1, 2, 2.5 ]


# In[5]:


#A = [  2, 3, 1, 0.1 ]
#d = [ .4, 1.0, .2, 1.5 ]
#f = [   0.3, 10, 0.2, 0.25 ]


# In[6]:


x = A[0]*np.sin(t*f[0])*np.exp(-d[0]*t) + A[1]*np.sin(t*f[1])*np.exp(-d[1]*t)
y = A[2]*np.sin(t*f[2])*np.exp(-d[2]*t) + A[3]*np.sin(t*f[3])*np.exp(-d[3]*t)


# In[7]:


plt.plot(x,y,'k',linewidth=0.1)
plt.axis('off')
plt.show()


# In[8]:


plt.plot(x,linewidth=.5)
plt.show()


# In[9]:


plt.plot(y,linewidth=.5)
plt.show()


# In[10]:


plt.plot(np.sin(t*f[0])*np.exp(-d[0]*t),linewidth=0.5)
plt.show()


# In[ ]:


