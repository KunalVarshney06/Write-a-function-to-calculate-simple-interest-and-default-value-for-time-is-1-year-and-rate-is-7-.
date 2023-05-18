# Write-a-function-to-calculate-simple-interest-and-default-value-for-time-is-1-year-and-rate-is-7-.
def cal(p,r=7, t=1)
  l= (p*r*t)/100
  return l
print(cal(4000)) 
print(cal(4000,10)) 
print(cal(4000,10,5))
