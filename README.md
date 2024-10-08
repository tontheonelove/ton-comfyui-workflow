# ton-comfyui-workflow

ComFy UI Portable use python for update custom node 

Goto path =>> python_embeded   and run below (..\\ is example please point to you destination node)

#python.exe -s -m pip install -r ..\ComfyUI\custom_nodes\........\requirements.txt


# Fix Can't install VLM nodes in ComfyUI

Install llama_cpp_python by using whl file from https://github.com/abetlen/llama-cpp-python/releases.

download pkg and past file =>>>  ComfyUI_windows_portable\python_embeded

run  =>> python.exe -m pip install llama_cpp_python-0.3.1-cp311-cp311-macosx_10_9_x86_64.whl      (this case on python 3.11)

restart Confy is done !!!
