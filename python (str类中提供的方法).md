python_str类中提供的方法
```python
class str(object):
    """
    str(object='') -> str
    str(bytes_or_buffer[, encoding[, errors]]) -> str
    
    Create a new string object from the given object. If encoding or
    errors is specified, then the object must expose a data buffer
    that will be decoded using the given encoding and error handler.
    Otherwise, returns the result of object.__str__() (if defined)
    or repr(object).
    encoding defaults to sys.getdefaultencoding().
    errors defaults to 'strict'.
    """
    def capitalize(self): # real signature unknown; restored from __doc__
        """
        首字母大写
        """
        return ""

    def casefold(self): # real signature unknown; restored from __doc__
        """
        大写转小写
        """
        return ""

    def center(self, width, fillchar=None): # real signature unknown; restored from __doc__
        """
       设置宽度（width），并将内容居中；fillchar（空白位置填充字符）
        """
        return ""

    def count(self, sub, start=None, end=None): # real signature unknown; restored from __doc__
        """
        统计字符（子序列）出现的次数,可设置起始位置和结尾位置
        """
        return 0

    def encode(self, encoding='utf-8', errors='strict'): # real signature unknown; restored from __doc__
        """
        指定的编码格式编码字符串
        """
        return b""

    def endswith(self, suffix, start=None, end=None): # real signature unknown; restored from __doc__
        """
        判断字符串以什么结尾
        """
        return False

    def expandtabs(self, tabsize=8): # real signature unknown; restored from __doc__
        """
        指定Tab(\t)所占位置个数 
        """
        return ""

    def find(self, sub, start=None, end=None): # real signature unknown; restored from __doc__
        """
        获取第一个子序列的位置
        """
        return 0

    def format(self, *args, **kwargs): # known special case of str.format
        """
        将一个字符串中的占位符（用“｛｝”表示）替换为指定的值
        """
        pass

    def format_map(self, mapping): # real signature unknown; restored from __doc__
        """
        将一个字符串中的占位符（用“｛｝”表示）替换为指定的值(以字典方式上传)
        """
        return ""

    def index(self, sub, start=None, end=None): # real signature unknown; restored from __doc__
        """
        获取第一个子序列的位置
        """
        return 0

    def isalnum(self): # real signature unknown; restored from __doc__
        """
        判断字符串中是否只包含字母或数字
        """
        return False

    def isalpha(self): # real signature unknown; restored from __doc__
        """
        判断字符串中是否只包含字母,汉字
        """
        return False

    def isdecimal(self): # real signature unknown; restored from __doc__
        """
        判断字符串中是否只包含数字
        """
        return False

    def isdigit(self): # real signature unknown; restored from __doc__
        """
        判断字符串中是否只包含数字，支持“②”
        """
        return False

    def isidentifier(self): # real signature unknown; restored from __doc__
        """
        S.isidentifier() -> bool
        
        Return True if S is a valid identifier according
        to the language definition.
        
        Use keyword.iskeyword() to test for reserved identifiers
        such as "def" and "class".
        """
        return False

    def islower(self): # real signature unknown; restored from __doc__
        """
        判断字符串都是小写
        """
        return False

    def isnumeric(self): # real signature unknown; restored from __doc__
        """
        判断字符串中是否只包含数字，支持“二”
        """
        return False

    def isprintable(self): # real signature unknown; restored from __doc__
        """
       判断字符串中是否存在\t,\n等不可见字符
        """
        return False

    def isspace(self): # real signature unknown; restored from __doc__
        """
        判断字符串是否全为空格
        return False

    def istitle(self): # real signature unknown; restored from __doc__
        """
        判断字符串中是否是标题（每个单词首字母大写）
        """
        return False

    def isupper(self): # real signature unknown; restored from __doc__
        """
        判断字符串是否全为大写
        """
        return False

    def join(self, iterable): # real signature unknown; restored from __doc__
        """
        将字符串的在每一个元素设置间隔符
        """
        return ""

    def ljust(self, width, fillchar=None): # real signature unknown; restored from __doc__
        """
       内容靠左
        """
        return ""

    def lower(self): # real signature unknown; restored from __doc__
        """
        大写转小写
        """
        return ""

    def lstrip(self, chars=None): # real signature unknown; restored from __doc__
        """
       删除字符串中靠左的指定字符（默认是空白符）
        """
        return ""

    def maketrans(self, *args, **kwargs): # real signature unknown
        """
        将指定字符替换
        """
        pass

    def partition(self, sep): # real signature unknown; restored from __doc__
        """
        按指定的字符做分割(从前往后)
        """
        pass

    def replace(self, old, new, count=None): # real signature unknown; restored from __doc__
        """
        S.replace(old, new[, count]) -> str
        
        Return a copy of S with all occurrences of substring
        old replaced by new.  If the optional argument count is
        given, only the first count occurrences are replaced.
        """
        return ""

    def rfind(self, sub, start=None, end=None): # real signature unknown; restored from __doc__
        """
        S.rfind(sub[, start[, end]]) -> int
        
        Return the highest index in S where substring sub is found,
        such that sub is contained within S[start:end].  Optional
        arguments start and end are interpreted as in slice notation.
        
        Return -1 on failure.
        """
        return 0

    def rindex(self, sub, start=None, end=None): # real signature unknown; restored from __doc__
        """
        S.rindex(sub[, start[, end]]) -> int
        
        Like S.rfind() but raise ValueError when the substring is not found.
        """
        return 0

    def rjust(self, width, fillchar=None): # real signature unknown; restored from __doc__
        """
        S.rjust(width[, fillchar]) -> str
        
        内容靠右
        """
        return ""

    def rpartition(self, sep): # real signature unknown; restored from __doc__
        """
        按指定的字符做分割(从后往前)
        """
        pass

    def rsplit(self, sep=None, maxsplit=-1): # real signature unknown; restored from __doc__
        """
        按指定的字符做分割(可以指定分割次数)
        """
        return []

    def rstrip(self, chars=None): # real signature unknown; restored from __doc__
        """
        删除字符串中靠右的指定字符（默认是空白符）
        """
        return ""

    def split(self, sep=None, maxsplit=-1): # real signature unknown; restored from __doc__
        """
        S.split(sep=None, maxsplit=-1) -> list of strings
        
        Return a list of the words in S, using sep as the
        delimiter string.  If maxsplit is given, at most maxsplit
        splits are done. If sep is not specified or is None, any
        whitespace string is a separator and empty strings are
        removed from the result.
        """
        return []

    def splitlines(self, keepends=None): # real signature unknown; restored from __doc__
        """
        根据换行符分割，True包含\n False不包含
        """
        return []

    def startswith(self, prefix, start=None, end=None): # real signature unknown; restored from __doc__
        """
        判断字符串以什么开头
        """
        return False

    def strip(self, chars=None): # real signature unknown; restored from __doc__
        """
        删除字符串中左右两边的指定字符（默认是空白符）
        """
        return ""

    def swapcase(self): # real signature unknown; restored from __doc__
        """
        大小写互换
        """
        return ""

    def title(self): # real signature unknown; restored from __doc__
        """
        将字符串转换为标题
        """
        return ""

    def translate(self, table): # real signature unknown; restored from __doc__
        """
        根据参数table给出的表(包含 256 个字符)转换字符串的字符, 要过滤掉的字符放到 
         del 参数中。
        """
        return ""

    def upper(self): # real signature unknown; restored from __doc__
        """       
        转大写
        """
        return ""

    def zfill(self, width): # real signature unknown; restored from __doc__
        """
        指定长度的字符串，原字符串右对齐，前面填充0。
        """
        return ""
 ```
