# Functions

```c
int	ft_strcmp(char *str1, char *str2)
{
	size_t	i;

	i = 0;
	while (str1[i] && str2[i] && str1[i] ! = str2[i])
		i++;
	return (i);
}
```
