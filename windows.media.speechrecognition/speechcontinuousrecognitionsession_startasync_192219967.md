---
-api-id: M:Windows.Media.SpeechRecognition.SpeechContinuousRecognitionSession.StartAsync(Windows.Media.SpeechRecognition.SpeechContinuousRecognitionMode)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncAction StartAsync(Windows.Media.SpeechRecognition.SpeechContinuousRecognitionMode mode)
-->

# Windows.Media.SpeechRecognition.SpeechContinuousRecognitionSession.StartAsync

## -description
*Overload*

Asynchronously begin a continuous speech recognition session with the specified [SpeechContinuousRecognitionMode](speechcontinuousrecognitionmode.md) behavior.

## -parameters
### -param mode
The speech recognition behavior.

## -returns
An asynchronous handler called when the operation is complete.

## -remarks
[CompileConstraintsAsync](speechrecognizer_compileconstraintsasync_1901700993.md) must always be called before StartAsync, even if no constraints are specified in the [Constraints](speechrecognizer_constraints.md) property.

## -examples

## -see-also
StartAsync, [PauseAsync](speechcontinuousrecognitionsession_pauseasync_576113822.md), [StopAsync](speechcontinuousrecognitionsession_stopasync_1648475005.md), [CancelAsync](speechcontinuousrecognitionsession_cancelasync_1837883523.md), [Speech interactions](https://docs.microsoft.com/windows/uwp/input-and-devices/speech-interactions), [Speech design guidelines](https://docs.microsoft.com/windows/uwp/input-and-devices/speech-interactions), [Speech recognition and speech synthesis sample](https://go.microsoft.com/fwlink/p/?LinkID=619897)
