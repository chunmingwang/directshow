# directshow preview
Still under construction

directshow example for VisualFBEditor
## amcap

IBasicVideo::GetCurrentImage
Retrieves the current image waiting at the renderer.
This method fails If the renderer Is Using DirectDraw acceleration. Unfortunately,
This depends On the End-user's hardware configuration, so in practice this method is not reliable.
A better way to obtain a sample from a stream in the graph is to use the ISampleGrabber interface.

but ISampleGrabber qedit.bi not being imported on freebasic

![amcap](https://github.com/chunmingwang/directshow/assets/35757455/6ed1f4ce-73b5-43b6-9b26-9f34478a11ee)

Audio format dialog

![image](https://github.com/chunmingwang/directshow/assets/35757455/b0be6ea0-b679-493b-be55-89a547781244)

Audio capture filter dialog

![image](https://github.com/chunmingwang/directshow/assets/35757455/9f19d925-75c8-4a79-9831-bcf7f159e2aa)

Video capture filter dialog

![image](https://github.com/chunmingwang/directshow/assets/35757455/23af377b-c0af-4659-9eff-d6603c4a7269)

Video capture pin dialog

![image](https://github.com/chunmingwang/directshow/assets/35757455/11650faa-3e68-4e4e-be02-e92e2b1702cf)

## playcap

![playcap](https://github.com/chunmingwang/directshow/assets/35757455/8234ac9a-d83a-4ce9-8f15-38b5d32b5815)

## sysenum

![sysenum](https://github.com/chunmingwang/directshow/assets/35757455/d166f9e6-4774-4785-adce-2789f187c01f)
