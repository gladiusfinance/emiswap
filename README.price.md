# Pricedump contract README

�������� ������������ ��� ��������� ���������� � ����� ������� �� ������ ���� Uniswap ����� ��������.

## ������ ���������

### getCoinPrices
����� ��������� �� ���� ������ ������� �������, ��� ������� ���������� �������� ���� � ������-��������� �� �����, � ������� ���������� �������� ��� ����.
����� ���������� ������ ��� ��������� ������� �� ��������� � DAI, ���������� �� 100000 (10 � ������� 5) ��� ���������� ������ ����������.
�.�. ��� ��������� ������ ���� � ��������� �� 5 ����� ����� ������� ���������� ���������� �������� �������� � ������� � ��������� ������ � �������� �� 100000.
���� ���� ��� ������-�� ������ ���������� �� �������, � ��������������� ������� ������������ 0.

�������� ��������� _market:
 - 0: ���� ����������� �����
 - 1: ����� Uniswap
 - 2: ����� Mooniswap

```solidity
  function getCoinPrices(address [] calldata _coins, uint8 _market) external view returns(uint[] memory prices)
```