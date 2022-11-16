// Função para transformar texto em voz

function falacte(pText)
                          {
							try{
                        	  var synth = window.speechSynthesis;
                        	  var utterThis = new SpeechSynthesisUtterance(pText);
                        	  utterThis.pitch = 1;
                        	  utterThis.rate = 2.5    ;
                        	  synth.speak(utterThis);
                        
                        	  utterThis.onpause = function(event) {}
							}
							catch(err) {}
                        	 };
