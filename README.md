def reverse_string(input_string):  
    """  
    反转给定的字符串。  

    参数:  
    input_string (str): 要反转的字符串。  

    返回:  
    str: 反转后的字符串。  
    """  
    return input_string[::-1]  

# 示例用法  
original = "Hello, World!"  
reversed_string = reverse_string(original)  
print(f"原始字符串: {original}")  
print(f"反转后的字符串: {reversed_string}")
