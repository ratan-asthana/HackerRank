# HackerRank
**Solutions to HackerRank Problems** 
# a simple solution as per the given data

if __name__ == '__main__':
    n = int(input())
    arr = map(int, input().split())
    arr_list = set(list(arr))
    arr_list_sorted = sorted(arr_list, reverse=True)
    print(arr_list_sorted[1])
