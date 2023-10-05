


- SSH key
```bash
cat /Users/yifanli/.ssh/id_rsa.pub

cat /Users/yifanli/.ssh/id_rsa
```



- Polyrepo
```
polyrepo list | grep 
polyrepo list | grep p2p
```

### Accessories
```sh 
#Jabra Headphone

sudo update "/Applications/Jabra Direct.app/Contents/MacOS/Jabra Direct"
```

### Metrics
```

    // TODO: do not hardcode suspected_scam
//    counter.labels("suspected_scam", wasFlagged.toString()).inc()

//    riskAssessmentCounter(result.suspectedMisdirectedPayment, "suspectedMisdirectedPayment")
//    riskAssessmentCounter(result.paymentBlocked, "paymentBlocked")
//    riskAssessmentCounter(result.refundToSvb, "refundToSvb")
  }

//  private fun riskAssessmentCounter(result:Boolean, label:String) = metric.counter(
//    name=label,
//    help="",
//    builder=Counter.Builder.() -> Unit = {}
//  )

//  override fun counter(
//    name: String,
//    help: String,
//    builder: Counter.Builder.() -> Unit,
//  ): Counter = Counter.build(name, help)
//    .apply(builder)
//    .create()
//    .register(registry.prometheusRegistry)
}

```
