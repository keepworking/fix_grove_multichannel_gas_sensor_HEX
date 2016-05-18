# fix_grove_multichannel_gas_sensor_HEX

우선 isp단자에 핀헤더를 납땜해주시고, 해당 핀헤더에 isp업로더를 연결,

grove_MCG.hex파일을 다운로드 뒤, isp업로더를 통해서 해당 hex파일을 올려줍니다.


avrdude 사용시 다음의 명령으로 업로드가 가능합니다.

cmd > avrdude -p m168 -c usbtiny -U flash:grove_MCG.hex -F


다른 avr개발환경(avr studio)에서 업로드를 하셔도 HEX파일을 통해 업로드가 가능합니다.

