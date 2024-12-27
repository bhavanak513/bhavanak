



global_var = 10 
global_uninit = None  

def func():
    static_var = 10 
    local_var = 10  
    heap_var = ctypes.pointer(ctypes.c_int(10))  

    # Print memory addresses
    print(f"Global initialized variable: {id(global_var)}")
    print(f"Global uninitialized variable: {id(global_uninit)}")
    print(f"Static variable: {id(static_var)}")
    print(f"Local variable: {id(local_var)}")
    print(f"Heap variable: {id(heap_var.contents)}")

def main():
    print(f"Code (function address): {id(func)}")
    func()

if __name__ == "__main__":
    main()















   
   "metadata": {},
   "source": [
"metadata":
"\n",
"celldata": {},
"source":{};
"\n":
"celldata":"markdown",
"\n",
"\n",
    "\n",
    "      :'\",<>/?|\\!@#%^&*~-+\n",
    "       \n",
    
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "my_dogs = 2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "my_dogs"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "my_dogs = ['Sammy', 'Frankie']"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "my_dogs"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
  
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
 
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "a = 5"
   ]
  },
  {
  
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "a"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
   
  "a =10":
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [

   "metadata": "code",
   "outputs": [],
   "source": [
   "outputs": [],
   "cell_type": "code"
   
    "a = 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   
   "source": [
   
    "a"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
   
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],

   
   "source": [
   "exe":
   "metadta" :[}
  
    "a + a"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
   
   ]
  },
  {
 
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "a = a + 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
  
    "a"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [

   "execution": "code"
   
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "a += 10"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [

   
    "a"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "a *= 2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "a"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
"type(a)"
]  
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "a = (1,2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "type(a)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [   
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "my_income = 100\n",
    "tax_rate = 0.1\n",
    "my_taxes = my_income * tax_rate"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
   
    "my_taxes"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
   ]
  }
 ],
 "metadata": {
  "kernelspec": { 
  },
  "language_info": {
   "codemirror_mode": {
   },
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
"nbformat_mode":{
"nbformat" : 5,
