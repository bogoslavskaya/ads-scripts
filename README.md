1. keywordsWithLowCtr ищет ключевые слова, у которых CTR ниже чем CTR группы
2. trackingCpcChanges отслеживает изменения cpc кампании в разрезе "последние 7 дней по сравнению с предыдущим периодом" и вешает соответсвующие ярлыки на кампании
3. QualityScoreandCost - ключи с QS<6 и тратами больше 40 грн
4. clicks>120conv<1reports - кампании, у которых > 120 кликов и 0 конверсий
5. matchtypeAndAvpos - ключи с фразовым соответствием и ср.позицией больше 2.3
6. SearchRankLostImpressionShare - кампании, у которых более 10% потеряных показов по ранку
7. capmCostToBudget - кампании, которые тратят больше 5% общего бюджета
8. CostTracking проверяет чтобы стомость за посл.2 дня не была ниже 15% от стоимости за предыдущую неделю и отпраляет оповещение на почту
