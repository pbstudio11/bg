68Found a 'popover' attribute. If you are testing the popover API, you must enable Experimental Web Platform Features. If not, note that custom attributes must start with 'data-': <URL>. This usage will *likely cause site breakage* when the popover API ships: <URL>.
consoleObservable.mjs:23 [copilot-chat] failed to publish custom instructions TypeError: t.filter(...).toSorted is not a function
    at _ (instruction-rules.ts:174:6)
    at g (instruction-rules.ts:125:29)
    at k.update (instruction-rules-publisher.ts:245:7)
    at async Syn.updateInstructionRules (copilot-chat-manager.tsx:301:5)
    at async index-Xk6DLUqf.js:184:50532
r.<computed> @ consoleObservable.mjs:23
httpRequest.mjs:35 Cross-Origin Read Blocking (CORB) blocked cross-origin response https://api.github.com/_private/browser/rum?ddforward=%2Fapi%2Fv2%2Frum%3Fddsource%3Dbrowser%26dd-api-key%3DeyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaEpJaEpoZFhSb1pXNTBhV05oZEdWa0Jqb0dSVlE9IiwiZXhwIjoiMjAyNi0xMS0yMFQxNjowNzo1Ny41MzNaIiwicHVyIjoiYnJvd3Nlcl9zdGF0czpjbGllbnRfdG9rZW4ifX0--21e823f1f03ed7195d34a86b18c94139fcca2521%26dd-evp-origin-version%3D7.16.2%26dd-evp-origin%3Dbrowser%26dd-request-id%3D7a184bbe-d32f-40aa-8708-703f681a608d%26dd-evp-encoding%3Ddeflate%26batch_time%3D1795105754745%26_dd.api%3Dbeacon with MIME type application/json. See https://www.chromestatus.com/feature/5629709824032768 for more details.
Nn @ httpRequest.mjs:35
sendOnExit @ httpRequest.mjs:26
u @ batch.mjs:49
(anonymous) @ batch.mjs:15
(anonymous) @ observable.mjs:48
notify @ observable.mjs:48
s @ flushController.mjs:44
(anonymous) @ flushController.mjs:30
(anonymous) @ observable.mjs:48
notify @ observable.mjs:48
Dn.capture @ pageMayExitObservable.mjs:21
(anonymous) @ addEventListener.mjs:122
i @ monitor.mjs:28
(anonymous) @ monitor.mjs:23
