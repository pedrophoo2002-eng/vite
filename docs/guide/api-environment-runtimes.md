{
  "config": {
    "company": {
      "name": "Sua Empresa",
      "industry": "Marketing Digital",
      "currency": "BRL",
      "currencySymbol": "R$"
    },
    "metrics": {
      "overview": {
        "revenue": {
          "label": "Receita Gerada",
          "enabled": true
        },
        "roi": {
          "label": "ROI (Retorno sobre Investimento)",
          "enabled": true
        },
        "cpl": {
          "label": "Custo por Lead (CPL)",
          "enabled": true
        },
        "cpa": {
          "label": "Custo por Aquisição (CPA)",
          "enabled": true
        },
        "leads": {
          "label": "Total de Leads",
          "enabled": true
        },
        "clients": {
          "label": "Clientes Ativos",
          "enabled": true
        }
      },
      "funnel": {
        "stages": [
          {
            "label": "Leads Gerados",
            "enabled": true
          },
          {
            "label": "Leads Qualificados",
            "enabled": true
          },
          {
            "label": "Propostas Enviadas",
            "enabled": true
          },
          {
            "label": "Fechamentos",
            "enabled": true
          }
        ]
      },
      "campaigns": {
        "channels": [
          "Google Ads",
          "Meta Ads",
          "Instagram",
          "LinkedIn"
        ],
        "metrics": [
          "CTR",
          "CPC",
          "Conversões",
          "Alcance"
        ]
      },
      "automation": {
        "emailEnabled": true,
        "whatsappEnabled": true,
        "crmEnabled": true
      }
    },
    "periods": {
      "default": "30d",
      "available": [
        "7d",
        "30d",
        "90d",
        "custom"
      ]
    }
  },
  "data": {
    "company": {
      "name": "Agência Digital Pro",
      "industry": "Marketing Digital"
    },
    "overview": {
      "revenue": {
        "value": "R$ 245.680",
        "change": "+12.5%",
        "changeType": "positive",
        "trend": "up"
      },
      "roi": {
        "value": "4.2x",
        "change": "+0.8x",
        "changeType": "positive",
        "trend": "up"
      },
      "cpl": {
        "value": "R$ 45",
        "change": "-5.2%",
        "changeType": "positive",
        "trend": "down"
      },
      "cpa": {
        "value": "R$ 180",
        "change": "-8.1%",
        "changeType": "positive",
        "trend": "down"
      },
      "leads": {
        "value": "1.847",
        "change": "+23.4%",
        "changeType": "positive",
        "trend": "up"
      },
      "clients": {
        "value": "342",
        "change": "+18.7%",
        "changeType": "positive",
        "trend": "up"
      }
    },
    "funnel": [
      {
        "stage": "Leads Gerados",
        "value": 1847,
        "percentage": 100,
        "color": "hsl(var(--chart-1))"
      },
      {
        "stage": "Leads Qualificados",
        "value": 923,
        "percentage": 50,
        "color": "hsl(var(--chart-2))"
      },
      {
        "stage": "Propostas Enviadas",
        "value": 461,
        "percentage": 25,
        "color": "hsl(var(--chart-3))"
      },
      {
        "stage": "Fechamentos",
        "value": 342,
        "percentage": 18.5,
        "color": "hsl(var(--chart-4))"
      }
    ],
    "revenue": [
      {
        "date": "01/12",
        "revenue": 185000,
        "target": 200000
      },
      {
        "date": "05/12",
        "revenue": 195000,
        "target": 205000
      },
      {
        "date": "10/12",
        "revenue": 210000,
        "target": 210000
      },
      {
        "date": "15/12",
        "revenue": 225000,
        "target": 215000
      },
      {
        "date": "20/12",
        "revenue": 245000,
        "target": 220000
      },
      {
        "date": "25/12",
        "revenue": 245680,
        "target": 225000
      },
      {
        "date": "30/12",
        "revenue": 250000,
        "target": 230000
      }
    ],
    "campaigns": [
      {
        "channel": "Google Ads",
        "ctr": 3.2,
        "cpc": 2.45,
        "conversions": 145,
        "reach": 45600
      },
      {
        "channel": "Meta Ads",
        "ctr": 2.8,
        "cpc": 1.85,
        "conversions": 123,
        "reach": 62400
      },
      {
        "channel": "Instagram",
        "ctr": 4.1,
        "cpc": 1.65,
        "conversions": 89,
        "reach": 38200
      },
      {
        "channel": "LinkedIn",
        "ctr": 2.1,
        "cpc": 4.25,
        "conversions": 67,
        "reach": 18900
      }
    ],
    "automation": {
      "contactsImpacted": {
        "value": "12.436",
        "change": "+34.2%",
        "changeType": "positive"
      },
      "emailOpenRate": {
        "value": "24.8%",
        "change": "+2.3%",
        "changeType": "positive"
      },
      "whatsappResponses": {
        "value": "892",
        "change": "+18.9%",
        "changeType": "positive"
      },
      "automationROI": {
        "value": "6.8x",
        "change": "+1.2x",
        "changeType": "positive"
      }
    },
    "projections": {
      "nextMonthRevenue": {
        "value": "R$ 285.000",
        "confidence": "85%",
        "change": "+16.0%"
      },
      "targetAchievement": {
        "current": 89.7,
        "target": 100,
        "remaining": "R$ 25.320"
      }
    }
  }
}
