
장도강 — 2023.09.23. 오후 11:37
안녕하세요
strategy.entry("진입", strategy.long, qty = 내가 넣고 싶은 수량)

qty에 내가 넣고 싶은 수량을 넣으면 진입 비율을 조절할 수 있습니다
strategy.opentrades == 0 이면 첫 진입이니 30% 넣고
strategy.opentrades == 1 이면 두번째 진입이니 30% 넣고
strategy.opentrades == 2 이면 세번째 진입이니 40% 넣는 식으로 해야합니다!


