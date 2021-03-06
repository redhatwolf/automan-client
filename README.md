## COPYING ##
AutoMan v0.8.3.1
Copyright  (C) 2010-2011 Alibaba Group Holding Limited

## License ##
  ---------------------------------------------------------------------------
  Copyright (c) 2004 - 2005, Paul Rogers and Bret Pettichord
  Copyright (c) 2006 - 2008, Bret Pettichord
  All rights reserved.
  
  Redistribution and use in source and binary forms, with or without
  modification, are permitted provided that the following conditions are met:
  
  1. Redistributions of source code must retain the above copyright notice,
  this list of conditions and the following disclaimer.
  
  2. Redistributions in binary form must reproduce the above copyright
  notice, this list of conditions and the following disclaimer in the
  documentation and/or other materials provided with the distribution.
  
  3. Neither the names Paul Rogers, Bret Pettichord nor the names of contributors to
  this software may be used to endorse or promote products derived from this
  software without specific prior written permission.
  
  THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS ``AS
  IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
  THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
  PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDERS OR
  CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
  EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
  --------------------------------------------------------------------------
  (based on BSD Open Source License)

## About ##
AutoMan is a test automation solution developed by TaoBao UI Automation Team.
AutoMan includes test framework in client side and PageModel web service in
server side.

## Install ##
In order to use AutoMan client, you will need to do the following:
1. run 'gem build Rakefile' under root folder
2. 'gem install automan-0.8.gem'
3. run the example code under: \example

The source code is provided as-is and is based on BSD Open Source.

## Sample ##
	ie = IEModel.start('http://s.taobao.com')
	page = ie.cast(Taobao::Searchtaobao)                                 
	page.txt_search.set "test search"
	page.btn_search.click

## More ##
Download following doc to read more:
http://qa.taobao.com/wp-content/uploads/2011/06/AutomanUserMenuZH-CN.pdf