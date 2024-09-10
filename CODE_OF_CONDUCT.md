wallet_id: 2147483409
valid_until: 1725599495
seqno: 20
actions:
  - magic: "0xec3c86d"
    mode: 3
    msg:
      sum_type: MessageInternal
      message_internal:
        ihr_disabled: true
        bounce: true
        bounced: false
        src: ""
        dest: 0:b4f24a2b215aa6683481b5123e9529e860049868df9c6abf9811a460d20ec750
        value:
          grams: "50000000"
          other: {}
        ihr_fee: "0"
        fwd_fee: "0"
        created_lt: 0
        created_at: 0
        init: null
        body:
          is_right: true
          value:
            sum_type: JettonTransfer
            op_code: 260734629
            value:
              query_id: 0
              amount: "30473636176816"
              destination: 0:e4d5eb5fe304f15b12919a9d67b8911c02551c29355800b53298e051ceb6607c
              response_destination: 0:e4d5eb5fe304f15b12919a9d67b8911c02551c29355800b53298e051ceb6607c
              custom_payload: null
              forward_ton_amount: "0"
              forward_payload:
                is_right: true
                value:
                  sum_type: TextComment
                  op_code: 0
                  value:
                    text: "✅You claim: +91420.91 DOGS"
  - magic: "0xec3c86d"
    mode: 3
    msg:
      sum_type: MessageInternal
      message_internal:
        ihr_disabled: true
        bounce: false
        bounced: false
        src: ""
        dest: 0:e4d5eb5fe304f15b12919a9d67b8911c02551c29355800b53298e051ceb6607c
        value:
          grams: "693757467"
          other: {}
        ihr_fee: "0"
        fwd_fee: "0"
        created_lt: 0
        created_at: 0
        init: null
        body:
          is_right: false
          value:
            sum_type: TextComment
            op_code: 0
            value:
              text: "✅You claim: +2.08 TON"
extended: null
signature: eb6d772f26aac8a4093c675f6b8325ff35f618d0b3c982036b062e3fd19184a495543b1511ad279dcff4762872faf2619c2d70ae4ad2b99f3cf44447ad55050f
