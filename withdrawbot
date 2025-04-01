import ccxt

bybit = ccxt.bybit({
    'apiKey': 'BYBIT_API_KEY',
    'secret': 'BYBIT_SECRET',
})

# Parameters
coin = 'USDT'
amount = 10
address = 'YOUR_WHITELISTED_ADDRESS'
network = 'TRC20'
tag = None

# Withdraw
result = bybit.withdraw(
    code=coin,
    amount=amount,
    address=address,
    tag=tag,
    params={'chain': network}
)
print("Bybit withdrawal:", result)
